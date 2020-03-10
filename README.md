# mRNA-localisation-screening

#### SUMMARY OF WORKFLOW TO RUN THE SCORING PROGRAM

1. Using command line, cd into the location you wish the save repository.

    `cd LOCATION/LOCATION`

2. Clone the repository and cd into it.

    `git clone https://github.com/mkiourlappou/mRNA-localisation-screening.git`

    `cd mRNA-localisation-screening`
    
3. Create an 'answers' folder and a 'figures' folder.

    `mkidr src/answers/`
    `mkidr src/figures/`

4. Add the figures to test in the figures folder.

5. Cd in the folder containing the questionnaire.py script.

    `cd src`

6. Run questionnaire.py script.

    `python questionnaire.py questions.py answers/ figures/*`
