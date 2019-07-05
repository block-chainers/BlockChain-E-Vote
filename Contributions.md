# Contribution Guide

1. Fork this repo and clone it.
    ```$ git clone https://github.com/${YOUR_GITHUB_USERNAME}/BlockChain-E-Vote.git```

2. Add this repo as the upstream
    ```$ git remote add -f upstream https://github.com/block-chainers/BlockChain-E-Vote.git```

3. Create a new branch for your work and add a suitable name.
    ```$ git checkout -b ${BRANCH_NAME} upstream/master```

4. Always pull the newest version before pushing.
    ```$ git pull --rebase upstream master```

5. Overwrite your personal fork with the upstream.
    ```$ git push --force```

6. Push your changes to your personal fork and submit a pull request.
    ```$ git push -u origin ${BRANCH_NAME}``` for first time.
    ```$ git push``` afterwards
