# {{cookiecutter.project}}
{{cookiecutter.description}}

## Project Structure

<pre>
./
├── data            -> Directory to store raw/processed/interim data.
├── docs            -> Directory for the documentation files.
├── logs            -> Directory to store the log of the models trained.
├── models          -> Directory to save the trained model's weights.
├── notebooks       -> Directory contains all the notebooks used for experimentation.
├── outputs         -> Directory to store the outputs file like prediction csv.
├── poetry.lock     -> Poetry dependency lock file.
├── pyproject.toml  -> Poetry dependency file.
├── README.md
├── environment.yml -> Dependency file for conda environment. # TODO: Update
├── src             -> Library root
└── tests           -> Directory for test scripts.
</pre>

## Usage



## License

This package was made by {{cookiecutter.author}}. 

{%- if cookiecutter.license == "MIT" -%}

Content for MIT license.

{%- elif cookiecutter.license == "BSD" -%}

Content for BSD license.

{%- else -%}

     

{% endif %}
