# Naming Conventions for Data Apps

## Verbs

### Compose

Combine disparate data sources to compose a composite dataset. Compose differs from Merge in that Merge brings together similar data from disparate sources.

Primary operation is Pandas merge.

### Merge (Union)

Merge data similar data from different sources. Primary operation is typically Pandas concat. Think union.

### Calc

Derive a new value by applying some function.

### Get

Read and scrub.

### Read

Read the data from source into a dataframe.

### Scrub

"Scrub" accounts for all the operations made on data after it's read into a dataframe from the data source to make the raw data fit for use. It does not include doing calculations to derive new values, or merging data from other data sources. It does includes operations such as:

- Renaming columns
- Converting datatypes
- Filtering rows
- Dropping columns
- Applying missing value treatments
- Mapping values
- Adding constant values
