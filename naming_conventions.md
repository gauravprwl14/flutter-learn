# Flutter/Dart Naming Conventions Guide

A comprehensive guide to naming conventions in Flutter/Dart development, aimed at maintaining code readability and consistency across large projects.

## Table of Contents

1. [File and Folder Naming](#file-and-folder-naming)
2. [Class Components (Including Widgets)](#class-components-including-widgets)
3. [Variables (Local and Global)](#variables-local-and-global)
4. [State Variables](#state-variables)
5. [Routes](#routes)
6. [Local and Global Variables](#local-and-global-variables)
7. [Constants](#constants)

## File and Folder Naming

- **Convention**: Lowercase with underscores (snake_case)
- **Applies to**: Both Dart files and asset folders.
- **Example**: `user_profile.dart`, `image_assets/`, `login_page.dart`

## Class Components (Including Widgets)

- **Convention**: UpperCamelCase (PascalCase)
- **Applies to**: All class names, including Flutter widgets, models, controllers, and services.
- **Example**: `UserProfile`, `LoginPage`, `UserModel`, `AuthService`

## Variables (Local and Global)

- **Convention**: lowerCamelCase
- **Applies to**: All variable names, including constants.
- **Local Variable Example**: `userName`, `isLoggedIn`
- **Global Variable Example**: `globalUserName`, `appThemeColor`
- **Constant Example**: `final String defaultProfilePic = 'path/to/default.png';`

## State Variables

- **Convention**: lowerCamelCase with Prefixing
- **Applies to**: State variables in Flutter widget state classes, prefixed with an underscore for private variables.
- **Example**: `_isLoading`, `_userList`

## Routes

- **Convention**: Lowercase with underscores (snake_case) or UpperCamelCase
- **Applies to**: Route names, which can be strings or constants.
- **String Example**: `'/user_profile'`, `'/login_page'`
- **Constant Example**: `static const userProfileRoute = '/UserProfile';`

## Local and Global Variables

- **Local Variables Convention**: lowerCamelCase
- **Example**: `final userScore = calculateScore(users);`
- **Global Variables Convention**: lowerCamelCase, often prefixed to denote global scope.
- **Example**: `final globalAppKey = GlobalKey();`

## Constants

- **Convention**: lowerCamelCase or UPPER_SNAKE_CASE
- **Applies to**: Constant names, especially for compile-time constants.
- **Example**: `const maxProfilePicSize = 1024;`
- **UPPER_SNAKE_CASE Example**: `const MAX_RETRY_ATTEMPTS = 3;`

This guide aims to provide clear and concise naming conventions for Flutter/Dart developers, ensuring a consistent and readable codebase across projects.
