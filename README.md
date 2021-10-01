# extra-filters

## About the module

This is a module that extends the filter functionality of the gov-uk prototype kit, by adding and extra-filters file.

The extra filters file contains a list of custom filters that help to solve common prototyping challenges.

## Installation instructions

`npm install @chrissybarrett/extra-filters`

This will copy the "extra-filters.js" file to your protoype.

Next you will either need to modify your utils.js file to reference the new file by changing line 19 and 20 to:

  var extraFilters = require('../app/extra-filters.js')(env)
	var filters = Object.assign(coreFilters, extraFilters, customFilters)

Or you can run the autosetup script. To run the autosetup script.

cd /{Your Prorotype directory}/node_modules/@chrissybarrett/extra-filters

  `npm run autosetup`
        
## Contributing

If you’ve got an idea or suggestion you can:

* [get in touch with me on slack] @ChrisBarret_defra
