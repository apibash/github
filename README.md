# bash
bash.jruns.com - run your many scripts from text file list

    chmod +x jruns

    ./apicup.sh github_org_repos jruns-com github.txt

    sh .apicup/file_replace_string.sh "github.txt" "git@github.com:" "https:\/\/github.com\/"

    ./jruns.sh "git clone" github.txt

    ./jruns.sh "sh .apicup/get_project_from_git_url.sh" github.txt > projects.txt

    ./jruns.sh "rm -rf" projects.txt 

chmod +x projects
./projects rm -rf 

> Press return for all questions by keeping the defaults and empty passphrase. This will generate two files in the `~/.ssh` directory within your home directory:
>
> -   `~/.ssh/id_rsa`
> -   `~/.ssh/id_rsa.pub`
>
> Copy and paste the content of the newly-generated `id_rsa.pub` file into the account where your repository is hosted. In my case, this is GitLab.