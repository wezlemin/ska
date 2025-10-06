
# Ska - Front-End for Chemsheets/Scisheets

This project provides the front-end for accessing files on ChemSheets. The backend API can be used to retrieve media files, but there are concerns regarding the accessibility of paid content. It is suggested that better security measures be implemented to prevent unauthorised access.

## How to Use

1. **Check Your Own Chemsheets File:**
   * Get the Chemsheets file you're looking for on the Ska website.
   * Note the file name.

2. **Use Ska to Find Your File:**
   * Visit [Ska](https://wezlemin.github.io/ska/).
   * Enter the file name.
   * That's all!

## API Endpoint

To access media files, use the following endpoint:

```
https://scisheets.co.uk/wp-json/wp/v2/media?per_page=(1-100)&page=(1-302)
```

* **per_page**: Number of files per page (1-100)
* **page**: Page number (1-302)

## Takedown Requests

For takedown requests, contact:

**Email**: [wezlemington@outlook.com](mailto:wezlemington@outlook.com)
