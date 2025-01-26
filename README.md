Net Promoter Score (NPS) Tool
-----------------------------

### Overview

This project is a simple web-based Net Promoter Score (NPS) calculator. It parses a CSV file containing a score column of integer values from 0 to 10. It then computes an overall NPS based on the standard formula:

NPS = (Promoters - Detractors) / Total Respondents \* 100

*   **Promoters:** Scores of 9 or 10
    
*   **Passives:** Scores of 7 or 8
    
*   **Detractors:** Scores of 0 to 6

The Net Promoter Score (NPS) is a metric used to measure customer loyalty and satisfaction by asking customers a single question: "How likely are you to recommend our product or service to others?" Responses are rated on a scale from 0 to 10 and classified as Promoters (9-10), Passives (7-8), or Detractors (0-6). The score is calculated by subtracting the percentage of Detractors from the percentage of Promoters.

NPS is important because it provides a clear, actionable indicator of customer sentiment and helps businesses identify areas for improvement, boost retention, and drive growth through positive word-of-mouth. It’s a simple yet powerful tool for understanding how well a company meets customer expectations
    

### Features

1.  **Drag & Drop CSV Upload**
    
    *   Simply drag your CSV file onto the drop zone, or click it to select a file.
        
    *   Automatically verifies file size (max 10MB) and CSV format.
        
2.  **Real-Time Analysis**
    
    *   Counts total rows, valid rows, and invalid rows.
        
    *   Classifies scores into promoters, passives, and detractors.
        
3.  **Instant NPS Calculation**
    
    *   Displays the NPS value along with a summary table.
        
    *   Showcases a color-coded NPS range meter.
        
4.  **Exportable Results**
    
    *   A single click to download the NPS summary as a CSV file.
        

### How to Use

1.  **Clone or Download** this repository and open the index.html file in your web browser.
    
2.  **Upload a CSV** file with a score column.
    
3.  **View the Analysis** including a table, NPS score, and progress visualization.
    
4.  **Export** the summary data as a CSV file, if needed.
    

### CSV Format

*   Must include a header row with a score column (the name can include the word “score” in any case, e.g., Score, MyScore).
    
*   Each subsequent row should contain integer scores between 0 and 10 in that column.
    

### Technical Details

*   **Front-End Only:** This project uses pure HTML, CSS, and vanilla JavaScript.
    
*   **Dependencies:**
    
    *   Font Awesome (for icons)
        
    *   Google Fonts or system UI for styling (optional)
        
*   **Browser Compatibility:** Modern browsers (Chrome, Firefox, Edge, Safari).
    

### License

Feel free to use, modify, and distribute this tool for personal or commercial projects.

### Contributing

1.  Fork or clone the repo.
    
2.  Create a new branch with your feature or fix.
    
3.  Submit a pull request.
