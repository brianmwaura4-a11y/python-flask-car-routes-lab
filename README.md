# Car Routes Lab

A Flask application demonstrating dynamic routes for a car company.

## Features

- Default home route
- Dynamic car model route
- Car model lookup
- Different responses for existing and unavailable models

## Routes

| Method | Route | Description |
|---|---|---|
| GET | `/` | Displays the Flatiron Cars welcome message |
| GET | `/<model>` | Checks whether a car model exists |

## Example Responses

### Home

`/`

Returns:

```text
Welcome to Flatiron Cars
