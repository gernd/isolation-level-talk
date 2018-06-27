# Isoliation level talk

Talk about DB Isolation Levels given for [jambit](https://www.jambit.com)

# Starting the presentation 

## Basic setup

Download the repo and open index.html

## Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the presentation repo

5. Install dependencies (in the presentation folder)
   ```sh
   $ npm install
   ```

6. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

7. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

# Used Libs/Frameworks 
This talk is built using the awesome [reveal.js](https://github.com/hakimel/reveal.js) framework by [Hakim El Hattab](https://hakim.se/).
Reveal.js is licensed under the [MIT License](https://opensource.org/licenses/MIT).
Copyright (C) 2016 Hakim El Hattab, http://hakim.se
