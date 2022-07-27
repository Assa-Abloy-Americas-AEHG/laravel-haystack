<div align="center">
    
<img src="https://user-images.githubusercontent.com/29132017/181374518-043b0359-edd2-43de-9906-3f587ccef99d.png" width="200">


# Laravel Haystack
Beautifully simple database-driven job chains.

![Build Status](https://github.com/sammyjo20/saloon/actions/workflows/tests.yml/badge.svg)

</div>

## Introduction

Laravel Haystack is a beautifully simple package that allows you to have a job chain powered by the database. Since all of the jobs in the chain are stored in the database, memory usage is low and you can delay jobs or have long running jobs risking your memory. Laravel Haystack supports every queue connection/worker out of the box. (Database, Redis/Horizon, SQS)

This package is great if you are chaining thousands of jobs or if you are building an API integration which requires job throttling with middleware.

## Installation

```bash
composer require sammyjo20/laravel-haystack
```
> Requires Laravel 8+ and PHP 8.1

Coming soon... 🪐 
