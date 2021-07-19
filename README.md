# [**`Queen Env`**](https://pub.dev/packages/queen_env)

# **`Part of Queen Packages 👑`**

[![style: lint](https://img.shields.io/badge/style-lint-4BC0F5.svg)](https://pub.dev/packages/lint)

# Motivation

- this packages is made for `place` package
- but you can use it as you wish

# Content

- `loadEnv()` function to load the content of the .env file
- `env(String key)` function to get the value by the key in case the key does not exist it will return empty string
- `envOrNull(String key)` same as above but it will return null if the key does not exits

# example

```dart
await loadEnv();
final value = env('db_user');
print(value) // root

```

# bonus

this package will skip the content of your `.env` file ⏭

# What is next ?

- [ ] unit test
- [ ] update .env contents
