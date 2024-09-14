# Web Crawling with Multithreading

## Project Overview

This project involves the implementation of a web crawler that uses multithreading to efficiently extract data from the World Wide Web. The crawler is designed to process multiple requests simultaneously, making the data extraction process faster and more efficient. The implementation includes various components for handling and filtering URLs, extracting hyperlinks, and managing queues for web requests.

### Key Features:
- **Multithreading**: Utilizes multiple threads to handle web requests and data extraction concurrently.
- **Queue Data Structure**: Manages URLs to be visited and ensures efficient processing of web pages.
- **Regular Expressions**: Extracts hyperlinks from web pages while filtering out irrelevant or incorrect links.
- **Data Storage**: Stores the content of web pages into strings for further processing.

### Skills Learned:
- **Web Crawling**: Gained experience in designing and implementing a web crawler.
- **Multithreading**: Applied multithreading techniques for parallel data processing.
- **Queue Data Structure**: Used queues to manage URLs and track visited pages.
- **Regular Expressions**: Employed regular expressions to filter and extract hyperlinks.
- **C++ Programming**: Developed the crawler using C++, focusing on performance and efficiency.

### Code Overview

The project includes a C++ implementation of a multithreaded web crawler. Key components of the code:

- **`FilterLinks` Function**: Filters out irrelevant or malformed hyperlinks.
- **`WriteCallback` Function**: Handles the data received from web requests.
- **`getSeeds` Function**: Extracts hyperlinks from the fetched web page and adds them to the queue.
- **`sendURL` Function**: Manages the crawling process, ensuring URLs are visited and processed.
- **`main` Function**: Starts the crawler with multiple threads to handle different initial URLs.

### How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mozeb-Ahmed-Khan/Web-Crawling-With-Multithreading.git

2. **Navigate to the Project Directory**:
   ```bash
   cd Web-Crawling-With-Multithreading

3. **Compile the Code**: Ensure you have a C++ compiler and necessary libraries installed. Compile the project using:
   ```bash
   g++ -std=c++11 -o web_crawler main.cpp -lcurl

4. **Run the executable**:
   ```bash
   ./web_crawler

