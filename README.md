# Django

1. 프로젝트 생성
```bash
django-admin startproject (pjt_name) .
```

2. venv
```bash

```

3. 가상환경 활성화
```bash
source venv/Scripts/activate
```

4. 가상환경 내부에 django 설치
```bash
pip install django
```

5. 서버 실행 (종료: ` ctrl + c `)
```bash
python manage.py runserver
```

6. 앱 생성
```bash
django-admin startapp {app_name}
```

7. 앱 등록 (`setting.py`)
```python
INSTALLED_APPS [
    ...
    '{app_name}'
]
```