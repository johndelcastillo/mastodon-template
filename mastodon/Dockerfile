FROM tootsuite/mastodon:latest

ARG LOCAL_DOMAIN REDIS_HOST REDIS_URL REDIS_PORT DB_HOST DB_USER DB_PASS DB_PORT SECRET_KEY_BASE OTP_SECRET VAPID_PRIVATE_KEY VAPID_PUBLIC_KEY SMTP_SERVER SMTP_PORT
ENV ES_ENABLED="false"

CMD ["/bin/bash", "-c", "rm -f /mastodon/tmp/pids/server.pid; bundle exec rails s -p 3000"]
