# Legislation-Scraping-Backend

Legislation-Scraping-Backend is a backend server project that provides a scraping tool in Node.js to extract legislative data from different states' government websites in the UK. It aims to gather legislative information such as bills, acts, and regulations from various sources and convert them into PDFs and CSVs for easier access and analysis. The scraped data is stored in a PostgreSQL database for further processing and retrieval.

## Features

### Web Scraping
- Utilizes the Cheerio library in Node.js for web scraping
- Scrapes legislative data from different states' government websites in the UK
- Extracts information such as bill titles, summaries, dates, and related documents

### PDF Conversion
- Converts scraped legislative data into PDF format
- Generates PDF documents containing bill details, summaries, and related information

### CSV Conversion
- Converts scraped legislative data into CSV format
- Generates CSV files with structured data for easy analysis and integration with other tools

### PostgreSQL Database
- Stores scraped legislative data in a PostgreSQL database
- Enables efficient data management, retrieval, and querying capabilities
- Supports indexing and search functionalities for faster data access

## Technologies Used

- Node.js: A JavaScript runtime for executing server-side applications
- Cheerio: A fast and flexible web scraping library for Node.js
- PDFKit: A PDF generation library for Node.js
- CSVWriter: A library for generating CSV files in Node.js
- PostgreSQL: A powerful relational database for storing and managing structured data

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- PostgreSQL database

### Installation

1. Clone the repository:

   ````shell
   git clone https://github.com/alirazaztdev1/legislation-scraping
   ```

2. Install dependencies:

   ````shell
   cd legislation-scraping-backend
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add the following environment variables:

   ````plaintext
   DATABASE_URL=your-postgresql-database-url
   ```

   Replace `your-postgresql-database-url` with the URL of your PostgreSQL database.

4. Run the server:

   ````shell
   npm start
   ```

   The server will start running at the specified port (default: 3000).

## Usage

Once the server is up and running, you can initiate the scraping process to gather legislative data from the different states' government websites. The scraped data can then be converted into PDFs or CSVs for further analysis and stored in the PostgreSQL database.

The specific implementation details, such as the states' government websites to scrape and the structure of the stored data, will depend on your project requirements. You can customize the scraping logic, PDF/CSV conversion, and database interactions accordingly.

## Contributing

Contributions to Legislation-Scraping-Backend are welcome! If you find any issues or want to add new features, feel free to submit a pull request. Please follow the existing code style and include appropriate tests.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use it for your own projects.

## Acknowledgements

- [Node.js](https://nodejs.org)
- [Cheerio](https://cheerio.js.org)
- [PDFKit](http://pdfkit.org)
- [CSVWriter](https://github.com/ryu1kn/csv-writer)
- [PostgreSQL](https://www.postgresql.org) 
- Any other libraries or resources used in your implementation

## Contact

If you have any questions or suggestions regarding Legislation-Scraping-Backend, please feel free to reach out to us:

- Email: [contact@legislation-scraping.com](mailto:contact@legislation-scraping.com)
- Website: [https://legislation-scraping.com](https://legislation-scraping.com)
- GitHub: [https://github.com/alirazaztdev1](https://github.com/alirazaztdev1)
