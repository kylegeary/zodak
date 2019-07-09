# Zodak: The Mystic Code Enforcer

## Problem
There is no standard of code formatting and linting across the UI team.

## Goal
Create a standard code format and linting enforcer to run on all new projects.

## Strategy
* Create a base Zodak configuration which can be used across all DEG projects.
* Create add-on options for specific project-types which can be added to the standard zodak config.
* Integrate Zodak with Orko, so new projects can be initiated with the correct Zodak config out of the box.

## Tools
* eslint
* prettier
* eslint-prettier-config
* babel