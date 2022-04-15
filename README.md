# JSON Resume Theme Standard Resume

> This theme builds upon and extends on the work EmaSuriano has done.
> JSON Resume theme based on Standard Resume style.


## Modifications

Below is the list of modifications:

* Fixed Invalid Date output when providing some dates
* Follow [jsonresume schema](https://jsonresume.org/schema/)
    * website -> url
    * company -> name
    * companies do not have an array of positions, each position is unique
    * replaced sample jsonresume with jsonresume schema sample
    * moved contact to the top for easy viewing
    * added a skills section

## How to use

We're going to use the official [resume-cli](https://github.com/jsonresume/resume-cli) to run our development server.

```bash
# Download official resume CLI
> npm install -g resume-cli

# Download Theme
> npm install -g jsonresume-theme-simplex

# Display your resume with the theme
> resume serve -t simplex
Preview: http://localhost:4000
Press ctrl-c to stop
```

## Development

[EmaSuriano](https://github.com/EmaSuriano) provided two scripts inside the `package.json`:

- `yarn start`: Generate `html` and `pdf` and host file on [http://localhost:3000/](http://localhost:3000/).
- `yarn html`: Generate `html` file and store it inside `/dev`.
- `yarn pdf`: Generate `pdf` file and store it inside `/dev`.

## License

Available under [the MIT license](http://mths.be/mit).

