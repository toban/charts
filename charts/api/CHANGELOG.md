# api

This chart does not yet follow SemVer.

## 0.3.0

- Optionally use a k8s secret instead of a plaintext value for the mailgun secret

## 0.2.0

- Switch docker file to PHP 7.4 and Laravel 7.x
- Change var name from `app.mail.driver` to `app.mail.mailer`
- Set `MAIL_MAILER` env var instead of `MAIL_DRIVER`

## 0.1.0

- First development version.
