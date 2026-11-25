# XC Ticket System

A legacy ASP.NET Web Forms ticket-management application with a companion ticket mailer.

## Architecture

- `TicketSystem/`: web UI, ticket operations, ASMX API and reports.
- `TicketMailer/`: desktop mailer project.
- `TicketSystem_Killhouse_Schema.sql`: existing database schema script.

## Development

Open `TicketSystem.sln` with compatible Visual Studio and ASP.NET Framework tooling. The web project targets .NET Framework 4.5. Restore packages and inspect database and mail configuration using disposable test resources.

## Status

Historical application, not a validated production release. Review authentication, dependencies, configuration and database scripts before deployment. Do not use live tickets, credentials or mail services during evaluation.
