# LaTex Resume Template 📜

## Introduction
Welcome to this Latex resume template, adapted from the fantastic starter template created by sb2nov. The goal of this fork is to provide a simplified, easy-to-follow guide for creating a beautiful and professional resume using LaTeX. This repo comes with four different templates in separate folders, suited for various backgrounds and career stages. The templates cover all common resume categories, such as experience, projects, skills, and education.

## Credits
We extend our gratitude to [sb2nov](https://github.com/sb2nov/) for his exceptional work in creating the foundational Latex resume template. His original template served as the basis for the improvements and adjustments in this adaptation.

## Prerequisites
To make the most of these templates, ensure you have the following installed:

1. A Unix-like operating system or Windows 10 with Linux Subsystem enabled (macOS, Ubuntu, Debian, CentOS, etc.)
2. TexLive - A fully featured LaTeX distribution. Visit <https://www.tug.org/texlive/quickinstall.html> for installation instructions.
3. Docker (optional) - Only required if you choose to use the Dockerfile included in this repo for a completely isolated environment. Refer to <https://docs.docker.com/engine/install/> for installation instructions.

## Template Selection
There are four available templates, each in its respective folder:

1. `skills_bottom_project` - Suitable for applicants with numerous projects and less experience.
2. `skills_bottom` - Ideal for applicants with fewer projects but richer experience.
3. `skills_top_project` - Perfect for applicants with balanced experience and projects.
4. `skills_top` - Geared towards experienced professionals with minimal projects.

## Using the Template (Terminal)
1. Choose the preferred template folder and navigate to it via your terminal or command line interface.
2. Within the chosen folder, find the `resume.tex` file and prepare your resume by filling in the required information.
3. Save the edited `resume.tex` file.
4. To compile the LaTeX code, type `pdflatex resume.tex` in your terminal or command line interface and press Enter.
5. Find the generated `resume.pdf` file in the same folder, ready for printing or submission.

## Using Docker (Optional)
If you opt to use Docker for a completely isolated environment, follow these steps:

1. Place the `resume.tex` file (filled with your personal info) in a separate folder.
2. Copy the provided `Dockerfile` to the same folder as the `resume.tex` file.
3. In the terminal or command line interface, navigate to the folder containing the `Dockerfile`.
4. Type docker build `-t mylatexenv .` and press Enter to build the Docker image.
5. Upon completion, type `docker run --rm -it -v "$(pwd)":/data mylatexenv pdflatex resume.tex` and press Enter to build the PDF.
6. Locate the generated `resume.pdf` file in the same folder as the `resume.tex` file.

## License
This project uses the MIT License. See the LICENSE file for details.

## Support
For questions or concerns regarding the template, submit an issue or contact us via email. I'm happy to help!

## Conclusion
Thank you for choosing this Latex resume template. With these simple steps, you can create a stunning and professional resume that stands out from others. Good luck with your job hunt! 💻
