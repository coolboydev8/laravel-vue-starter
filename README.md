## Laravel Vue.js 3 SPA Starter Boilerplate

A simple and clean boilerplate to start a new SPA project with authentication, user, roles, permissions management and more features. This boilerplate uses the following tools:

- [Laravel 10.x](https://github.com/laravel/laravel)
- [Laravel Sanctum](https://laravel.com/docs/10.x/sanctum)
- [Vue 3](https://github.com/vuejs/vue)
- [Vue Router](https://router.vuejs.org/)
- [Vuex](https://vuex.vuejs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [Vue I18n](https://vue-i18n.intlify.dev)
- [Laravel Request Docs](https://github.com/rakutentech/laravel-request-docs)

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Features

The following Sanctum features are implemented in this Vue SPA:

- ✅ Laravel 10
- ✅ Vue 3
- ✅ VueRouter + Vuex
- ✅ Vue I18n Multi Language
- ✅ Login
- ✅ Password Reset
- ✅ Registration
- ✅ Admin Panel
- ✅ Profile Management
- ✅ User Management
- ✅ Roles Management
- ✅ Permissions Management
- ✅ Password Change
- ✅ E-Mail Verification
- ✅ Posts Management
- ✅ Frontend Blog
- ✅ Bootstrap 5
- ✅ Automatic Api Documentation  -- route  /api-docs

## How To Use
#### Clone the repository

```bash
git clone https://github.com/coolboydev8/laravel-vue-starter.git
```

#### Copy .env.example file to .env and edit credentials also set app url

#### Install Via Composer

```bash
composer install
```

#### Generate Application Key

```bash
php artisan key:generate
```

#### Migrate Database

```bash
php artisan migrate
```

#### Run Seeder

```bash
php artisan db:seed
```

#### Install Node Dependencies

```bash
npm install or yarn install

npm run dev or yarn dev
```
#### Production

```bash
npm run build or yarn build
```

## Email Verification

To enable email verification make sure that your `App\User` model implements the `Illuminate\Contracts\Auth\MustVerifyEmail` contract.

## Contributing

Thank you for considering contributing to the project! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).    
The Vue framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).    
This repository is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT). 
