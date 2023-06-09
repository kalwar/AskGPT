# AskGPT

A very simple Symfony app used for learning Symfony 6 using OpenAI, ChatGPT API.

---

# Steps to follow

1. Simply run the app using Symfony command
2. First do, `composer install` to install dependencies
3. Symfony command: `symfony server:start -d` to start in daemon mode
4. Visit URL: https://127.0.0.1:8000/ to see running app
5. Make sure to add your ChatGPT API Secret Key in [.env file](https://github.com/kalwar/AskGPT/blob/e7c52584c548217059ee0df04442908d67422a12/.env#L23)
6. To stop the app execute: `symfony server:stop`
7. Feel free suggest new ideas or open PR

# Tech stack

1.  [Symfony](https://symfony.com/)
2.  [PHP](https://www.php.net/)
3.  [OpenAI](https://openai.com/)

# Symfony commands

```
symfony serve --help
symfony server:status
symfony server:stop
symfony serve -d

composer require templates
symfony console

php bin/console debug:router


```

# Use for reference

Use solely for reference material only
