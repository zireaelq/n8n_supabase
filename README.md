
# Self-hosted Supabase + n8n

Настроенная среда для самостоятельного хостинга Supabase + n8n. Nocode development.

## Начало работы

### Необходимые требования

Перед началом убедитесь, что установлены:
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Настройка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/zireaelq/n8n_supabase.git
   cd n8n_supabase/
   ```

2. Скопируйте пример файла переменных окружения и настройте его:
   ```bash
   cp .env.example .env
   ```

3. Запустите сервисы:
   ```bash
   docker-compose up -d
   ```

4. Доступ к сервисам:
   - Необходим домен
   - Supabase Studio: пробросить 8000 порт
   - n8n: настроен на поддомен n8n.*

