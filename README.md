# 🐘 PHP Starter

Bem-vindo ao **PHP Starter**, um repositório dedicado à documentação e acompanhamento dos meus estudos com a linguagem **PHP** — e aberto à comunidade!  
Aqui você encontrará projetos, anotações e exemplos práticos, todos organizados de forma modular, com cada exemplo/projeto rodando de maneira independente via [Composer](https://getcomposer.org/).

---

## 📁 Estrutura do Repositório

Cada diretório dentro de `Projetos/` corresponde a um projeto ou exemplo independente, inicializado com seu próprio `composer.json`. Isso permite que cada módulo seja explorado e executado individualmente, facilitando a aprendizagem incremental e o reaproveitamento de código.

```
.
├── Projetos/
│   ├── hello/
│   │   ├── composer.json
│   │   └── src/
│   │       └── index.php
│   └── projeto-2/
│       ├── composer.json
│       └── src/
├── docs/
│   └── anotacoes.md
├── .gitignore
├── LICENSE
└── README.md
```

Para executar qualquer projeto:
```sh
cd Projetos/hello
composer install
composer start
```

---

## 🎯 Objetivos

- Documentar o progresso e aprendizados em PHP
- Compartilhar códigos comentados e exemplos práticos
- Registrar resoluções de desafios, exercícios e problemas reais
- Servir de referência para mim e para a comunidade PHP

---

## Porque PHP?

PHP é uma linguagem pragmática, com um ecossistema maduro e uma evolução notável nas últimas versões (tipagem forte, enums, atributos, `match`, propriedades `readonly`).

- **Composer** facilita a gestão de dependências, autoload (PSR-4) e scripts.
- **PHP-CS-Fixer** e **PHP_CodeSniffer** mantêm o código padronizado.
- **PHPStan** e **Psalm** trazem análise estática e mais segurança de tipos.
- **PHPUnit** e **Pest** cobrem a parte de testes.
- O servidor embutido (`php -S localhost:8000`) permite testar sem configurar nada.
- A comunidade é enorme e a documentação oficial é rica em exemplos.

---

## 🛠️ Requisitos

- PHP 8.2 ou superior
- Composer 2.x

---

## 📚 Recursos Úteis

- [Site oficial do PHP](https://www.php.net/)
- [Manual do PHP (PT-BR)](https://www.php.net/manual/pt_BR/)
- [PHP: The Right Way (PT-BR)](https://phptherightway.com/pt_BR/)
- [Packagist (repositório de pacotes)](https://packagist.org/)
- [Awesome PHP (repositório de links)](https://github.com/ziadoz/awesome-php)

---

## 🐘 Contato

Dúvidas, sugestões ou feedback?  
Abra uma [issue](https://github.com/snake-outerheaven/php-starter/issues) ou entre em contato pelo [GitHub](https://github.com/snake-outerheaven).

---

Feito com paixão, dedicação e muitos elefantes!  
**snake-outerheaven**
