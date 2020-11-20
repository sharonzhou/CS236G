# Dev Instructions (for Mac)

1. Ensure `brew` is installed. The `brew` tool is a package manager for Mac that we will use to install the programming language `ruby`.

    If not, download `ruby` here: `https://brew.sh`

1. Install `ruby`

    ```bash
    brew install ruby
    ```

    The version of `ruby` you observe from running `/usr/local/opt/ruby/bin/ruby -v` should be greater than 2.5.

1. Change your `PATH` to include the `ruby` executable that was just installed (as opposed to the version of `ruby` that ships with OS X and is used by default) by replacing `<Your username>` in the following command and running it.

    ```bash
    echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> /Users/<Your username>/.bash_profile
    ```

1. Effectuate the change to your `PATH` by running the following (or you can alternatively just restart your shell).

    ```bash
    source ~/.bash_profile
    ```

    You can validate that your `PATH` was updated by running `echo $PATH`. You should see several paths demarcated from each other by colons ':'. Ensure that `/usr/local/opt/ruby/bin` (path to new `ruby`) shows up before `/usr/bin/` (path to old `ruby`).

1. Run the following which will download the dependencies for this project (listed in `Gemfile`).

    ```bash
    bundle install
    ```

1. Launch the website.

    ```bash
    ./run.sh
    ```

    You can access the website by going to the URL displayed under the label "Server address" (probably `http://127.0.0.1:4000/`)
