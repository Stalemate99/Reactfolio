# Reactfolio

Reactfolio is a CLI-based portfolio builder that allows you to create a minimalistic React portfolio by simply entering your details in a JSON file. It provides a super simple way to showcase your cool projects.


## About

Reactfolio aims to simplify the process of building and deploying a portfolio website. With Reactfolio, you can create a stylish and professional portfolio by just providing your details in a JSON file. It leverages the power of React, allowing you to showcase your projects and highlight your skills in an elegant manner.

Check out the demo of Reactfolio: [YouTube Demo](https://youtu.be/O7GDJ7d8MF0)

## Usage

To use Reactfolio, follow these steps:

1. Install Reactfolio globally:
   ```bash
   npm install -g reactfolio
2. Create a JSON file with your portfolio details. The JSON file should have the following structure:
    ```json
    {
    "name": "Your Name",
    "title": "Your Title",
    "description": "Your Description",
    "projects": [
      {
        "name": "Project Name 1",
        "description": "Project Description 1",
        "url": "Project URL 1"
      },
      {
        "name": "Project Name 2",
        "description": "Project Description 2",
        "url": "Project URL 2"
      }
    ]
   }
3. Run the Reactfolio CLI command and provide the path to your JSON file:
    ```bash
    reactfolio build /path/to/your/json/file.json
4. Reactfolio will generate a React portfolio based on your JSON file and save it in a build directory.
5. Deploy the generated portfolio using Surge:
    ```bash
    surge build/
Surge will automatically deploy your portfolio and provide you with a URL to access it.

## Customization
Reactfolio provides customization options to style your portfolio. You can modify the styles by editing the CSS file located in the build directory.

## Contributing
Contributions to Reactfolio are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request to the Reactfolio GitHub repository.

## License
This project is licensed under the MIT License.
