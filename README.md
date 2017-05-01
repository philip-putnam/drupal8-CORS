# Drupal 8 + Angular 2, using Angular-CLI

By: Philip Putnam

## Drupal 8 Side

## Setup

This setup instruction requires drush & composer on the command line

This setup/github works in conjunction with a "partner" github that contains the Angular 2 files, you will need to download both projects and place them in the same parent directory.

Drupal 8 files: https://github.com/philip-putnam/drupal8-CORS
Angular 2 files: https://github.com/philip-putnam/angular2-drpl8

In terminal, navigate to Drupal 8 project main/root directory, then follow these directions:

1. drush dl cors
2. drush en cors
3. composer require stack-cors
