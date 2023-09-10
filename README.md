# project-nuxtjs

## Build Setup ビルド・セットアップ

```bash
# install dependencies 依存関係をインストール
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

【訳】どのように機能するかについての詳しい説明は、[ドキュメント](https://nuxtjs.org)をご覧ください。  

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.  

【訳】以下の追加ディレクトリを作成することができ、そのうちのいくつかは特別な動作をします。pagesだけは必須です。（pages以外のｈディレクトリは、）それぞれの機能を使いたくなければ削除してもかまいません。

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.  

【訳】assets ディレクトリには、Stylus や Sass ファイル、画像、フォントなどのコンパイルされていないアセットが含まれます。（訳注：Stylusとはブラウザ拡張機能の一つです）

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).  
【訳】このディレクトリの使い方については、[ドキュメント](https://nuxtjs.org/docs/2.x/directory-structure/assets)を参照してください。

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.  
【訳】componentsディレクトリには、Vue.jsコンポーネントが含まれます。コンポーネントは、ページのさまざまな部分を構成し、再利用したり、ページやレイアウト、さらには他のコンポーネントにインポートしたりすることができます。


More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).  
【訳】このディレクトリの使い方については、[ドキュメント](https://nuxtjs.org/docs/2.x/directory-structure/components)を参照してください。

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).

### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).
