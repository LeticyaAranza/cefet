# Estágio Revisão — CEFET-MG

Projeto Django para a Mostra de Cursos.

## Como executar no Windows

Abra o terminal dentro da pasta `estagioquiz`:

```powershell
py -m venv venv
venv\Scripts\activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Depois abra `http://127.0.0.1:8000/`.

## Importante

O projeto original estava com alguns problemas:
- imagens e vídeo referenciados nos templates não estavam no projeto;
- os quizzes de Informática e Edificações carregavam o JavaScript com caminho relativo incorreto;
- os componentes dos quizzes continham `html`, `head` e `body` dentro de páginas que já possuem esses elementos;
- o quiz de Mecatrônica não tinha implementação JavaScript.

Esses pontos foram corrigidos nesta versão.
# Info-Meta
