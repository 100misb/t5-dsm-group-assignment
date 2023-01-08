## Objective :
1. Identify a brand you would like to follow on Twitter.
2. Extract the data from Twitter for that brand using either brand name or hashtags
associated with the brand or both.
3. Identify keywords, hashtags, and influencers most likely to play a role in the brand
campaign.
4. Identify the different groups here and the conversation surrounding the brand.

## Set up project

- Clone github repo
    ```zsh
    git clone https://github.com/100misb/t5-dsm-group-assignment.git
    ```

- Setup environment

    - To initialize a virtual Environment
        ```zsh
        python3 -m venv .dsm
        ```

    - Activate a virtual Environment for Mac/Linux :
        ```zsh
        source .dsm/bin/activate
        ```
    - Activate a virtual Environemnt for Windows : 
        ```bash
        .dsm\Scripts\activate
        ```
    
- Install all python dependecies/libraries
    ```zsh
    pip3 install -r requirements.txt
    ```

- For attaching virtual environment to jupyter kernel
  ```zsh
  ipython kernel install --user --name=.dsm
  ```

- The open the following codespace using 
  ```zsh
  jupyter-notebook . 
  ```
  Then select the virtual environment from `Kernel > Change Kernel > .dsm`
