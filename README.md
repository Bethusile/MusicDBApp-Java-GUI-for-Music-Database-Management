# MusicDBApp-Java-GUI-for-Music-Database-Management

A Java Swing-based desktop application that connects to a SQL Server database to manage and display music data including artists, albums, and tracks.

## Description

MusicDBApp is a lightweight database management system designed for music libraries. Built with Java Swing and JDBC, it provides an intuitive interface for interacting with a SQL Server database. Users can navigate through music entries and explore relationships between artists, albums, and songs.

## Technologies Used

- **Java SE**
- **Swing** (GUI framework)
- **JDBC** (Database connectivity)
- **SQL Server** (Relational database)

## Features

- Connects to SQL Server using JDBC
- Displays data in interactive GUI components (e.g., tables, dropdowns)
- Queries music data like artist names, album titles, and track details
- Event-driven responses to user interactions
- Modular structure for separating database logic and UI

## Getting Started

### Prerequisites
- JDK 8 or later
- SQL Server (with a populated Music database)
- JDBC SQL Server driver (`mssql-jdbc.jar`)

### Running the App
1. Ensure your SQL Server is running and accessible.
2. Update the database connection URL, username, and password in the source code.
3. Compile the Java files:
   ```bash
   javac *.java

