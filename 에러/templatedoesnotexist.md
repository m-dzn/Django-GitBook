# TemplateDoesNotExist

config 또는 프로젝트명으로 된 디렉토리의\
settings.py 파일의 `'DIRS': [ ]` 가 이렇게 비어있을 경우\
템플릿 경로를 추가해주면 해결됩니다.



> 프로젝트명/settings.py

```python
BASE_DIR = Path(__file__).resolve().parent.parent
TEMPLATE_DIR = Path(BASE_DIR, 'templates')

...

TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [TEMPLATE_DIR],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]
```
