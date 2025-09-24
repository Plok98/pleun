# Setup

## Environment

Before starting, make sure you have [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [NodeJS](https://nodejs.org/) installed.

Then install Jekyll:

```
$ gem install jekyll
```

And install Gulp client:

```
$ npm install gulp-cli -g
```

## Installing template

1. Fork the [Jekflix Template](https://github.com/thiagorossener/jekflix-template/fork)
2. Clone the repo you just forked:
```
$ git clone https://github.com/<your-github-username>/jekflix-template.git
```
3. Access the local project:
```
$ cd path/to/jekyll-template
```
4. Install npm packages:
```
$ npm install
```
5. Install Ruby dependencies:
```
$ bundle install
```
6. Build Jekyll:
```
$ bundle exec jekyll build
```
7. Then run Gulp:
```
$ gulp
```

## Running local

After the steps above, to run Jekyll locally, you'll just need to run Gulp:
```
$ gulp
```

## Customization

*Jekflix Template* allows you to personalize your site with several settings. See the [docs](settings.md#settings) for more details.

For advanced theme customization, check the directory `_sass` for style files.

## Translations

In order to translate texts throughout the theme, create a `translations.yml` file in `src/yml` and add the settings below.

> **Note:** If you're using the `gem`, just add it into your `_config.yml`.

```
translations:
  text:
    new_post: "Nieuw bericht"
    see_also: "Zie ook"
    search: "Zoeken"
    author: "Auteur"
    share: "Delen"
    comments: "Reacties"
  button:
    read_now: "Read Now"
    share_on_twitter: "Delen op Twitter"
    share_on_facebook: "Delen op Facebook"
  pagination:
    page: "Pagina"
    of: "van"
    next_page: "Volgende pagina"
    next_post: "Vorige pagina"
  recommendation:
    text: "Op naar de volgende alinea."
    back_btn: "Terug naar boven"
  error_404:
    title: "Helaas pindakaas, pagina niet gevonden :("
    message: "Sorry, de pagina die je zoekt bestaat niet (meer)."
    image_alt: "404 - Pagina niet gevonden"
  contact:
    title: "Stuur een bericht"
    subject: "New contact!"
    submit_btn: "Send"
    placeholders:
      name: "Jouw naam"
      email: "Jouw e-mail"
      message: "Jouw bericht"
    errors:
      locale: "nl"
      empty_name: "Naam is verplicht"
      empty_email: "E-mail is verplicht"
      invalid_email: "E-mail is verplicht"
      empty_message: "Bericht is verplicht"
    after_send:
      title: "Bericht verzonden!"
      message: "Bedankt voor je bericht! Ik kom er zo snel mogelijk bij je op terug.."
```