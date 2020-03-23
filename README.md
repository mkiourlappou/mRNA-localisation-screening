# mRNA-localisation-screening

#### PRE RUNNING CHECKS

1. In case of an `XCRUN: ERROR:` , update the xcode ny running the following in the command line:
`xcode-select --install`

2. Check python version by running `python -V` in the command line. If you have python 2 upgrade to python 3.

#### SUMMARY OF WORKFLOW TO RUN THE SCORING PROGRAM

1. Using command line, cd into the location you wish the save repository.

    `cd LOCATION/LOCATION`

2. Clone the repository and cd into it.

    `git clone https://github.com/mkiourlappou/mRNA-localisation-screening.git`

    `cd mRNA-localisation-screening`
    
3. Create an 'answers' folder and a 'figures' folder.

    `mkdir src/answers/`
    `mkdir src/figures/`

4. Add the figures to test in the figures folder.

5. Cd in the folder containing the questionnaire.py script.

    `cd src`

6. Run questionnaire.py script.

    `python questionnaire.py questions.py answers/ figures/*`
