# Docksal powered Drupal 9 With Composer Installation

This is a Drupal 9 with Composer installation pre-configured for use with Docksal.

## Setup instructions

### Step #1: Docksal environment setup

**This is a one time setup - skip this if you already have a working Docksal environment.**

Follow [Docksal environment setup instructions](https://docs.docksal.io/getting-started/setup/)

### Step #2: Project setup

1. Clone this repo into your Projects directory

    ```
    git clone git@bitbucket.org:webfirst/drupaltest.git
    
    ```

2. Go to your root directory
    ```
    cd drupaltest
    ```
3. Initialize the site

    This will initialize local settings and install the site via drush

    ```
    fin init
    ```

4. Point your browser to

    ```
    http://drupaltest.docksal
    ```

    When the automated install is complete the command line output will display the admin username and password.


5. Take your test.

    The questions will be provided in a seperate email just before your test
   start time.

    Please contact **_Ryan Lawson (rlawson@webfirst.com)_** If you haven't received such email.


6. Submit your test
   ```
    fin submit-test
   ```

    **webfirst-test.tar.gz** file will be generated in your project root directory.


7. Send that (**webfirst-test.tar.gz**) directory via email to **_Ryan Lawson (rlawson@webfirst.com)_**
