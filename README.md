# BookStore layouts

1. Make sure that you installed [webpacker](https://github.com/rails/webpacker):
```bash
yarn add @rails/webpacker
bundle exec rails webpacker:install
```

2. Then add needest packages:
```bash
yarn add jquery bootstrap-sass font-awesome
```

3. If you want, you can change the entrypoint folder from `app/javascript` to `app/webpack`. Make sure that you changed `source_path` in the `webpacker.yml` to the new folder.


