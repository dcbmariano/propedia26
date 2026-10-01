# Propedia 26 Web Application

> **Important:** Please check the latest version at https://github.com/LBS-UFMG/propedia26


This repository contains the source code of the **Propedia 26 web application**, the web interface for accessing and exploring version 26 of the Propedia database.

Propedia is a database dedicated to the structural characterization of **protein–peptide interactions**. The Propedia 26 web application provides an interactive interface for querying the database and accessing information associated with protein–peptide complexes.

## Technologies

The web application was developed using:

- **PHP**
- **CodeIgniter 4**
- **Composer**
- **MySQL** for database management
- **HTML, CSS, and JavaScript** for the web interface

The application follows the architecture and conventions provided by the CodeIgniter 4 framework.

## Project Structure

The main directories of the application include:

```text
propedia26/
├── app/          # Application source code
├── public/       # Publicly accessible files and application entry point
├── system/       # CodeIgniter framework files
├── tests/        # Automated tests
├── writable/     # Writable application files
├── .env          # Environment configuration
├── composer.json # PHP dependencies
└── spark         # CodeIgniter command-line utility
```

### `app/`

Contains the main application code, including controllers, models, views, configuration, and other components required by the Propedia 26 web application.

### `public/`

Contains the publicly accessible resources and the main entry point of the web application.

### `system/`

Contains the CodeIgniter 4 framework components.

### `tests/`

Contains automated tests associated with the application.

### `writable/`

Contains files generated or written by the application during execution, such as cache, logs, and other runtime data.

## Database

The web application connects to the Propedia 26 database to retrieve and present information about protein–peptide complexes.

The database includes structural and molecular information associated with Propedia 26 entries, allowing users to search and explore protein–peptide interactions through the web interface.

## Installation

Clone the repository:

```bash
git clone https://github.com/dcbmariano/propedia26.git
cd propedia26
```

Install the PHP dependencies using Composer:

```bash
composer install
```

Configure the application environment using the `.env` file, including the database connection parameters and other environment-specific settings.

The application can then be started using the CodeIgniter development server:

```bash
php spark serve
```

By default, the application will be available at:

```text
http://localhost:8080
```

## Configuration

Database and application-specific settings should be configured through the environment configuration file.

Do not commit sensitive credentials or production configuration files to the repository.

## Propedia 26

Propedia 26 provides an updated collection of protein–peptide structural information and associated molecular properties. The web application serves as an interface for accessing and exploring these data.

For information about the database, data processing pipeline, and dataset, please refer to the corresponding Propedia 26 resources and publications.

## Citation

If you use Propedia 26 or this web application in your research, please cite the corresponding Propedia 26 publication.

```text
Mariano et al. PROPEDIA 26: AN EXPANDED AND UPDATED DATABASE OF PROTEIN-PEPTIDE INTERACTIONS FOR MACHINE LEARNING APPLICATIONS. NAR. 2027.
```

## License

This project is distributed under the license specified in the repository.

## Repository

The source code and documentation are available at:

https://github.com/LBS-UFMG/propedia26

> **Important:** Please refer to the repository for the latest version of the code and documentation.
