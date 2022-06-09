Follow the instructions in the CircleCI 2.0 documentation to set up your first pipeline. Create a new repository in Github or select an existing repository. Don't go too far in the tutorial! We suggest you stop just before getting to the "Breaking Your Build" section.
Clone the repository to your local computer. Change to the branch Circle CI created.
Open the .circleci/config.yaml file with the code editor of your choice.

https://circleci.com/docs/2.0/getting-started/

Use the "requires" key to make your print_world job wait for the print_hello job to finish.

