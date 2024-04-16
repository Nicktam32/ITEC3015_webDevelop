# Takeaways:

1. Google Fonts for text CSS: 
    ```
    https://fonts.google.com/
    ```

2. Bootstrap for Responsive Website: 
    ```
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    ```

3. Data Visulization in amCharts, SVG

4. Data Manipulation in Json datatype by using JavaScript
     ``` 
     // Fetch data
            var wasteCatData = fetch("/data/solid-waste-disposal-quantity-by-category-en-2022.json")
                .then(response => response.json())
                .then(data => {
                    wasteCatData = data;
                    setInitialData();
                })
                .catch(error => console.error("Error loading JSON file", error));
     ```

5. Construst a Website in Express.js framework 