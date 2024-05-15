# ACCESS Evalulation Recipes

A loose collection of recipes to validate the performace of ACCESS climate and earth system models. The recipes in this repository are focussed on evaluating and validating model output on broad scales, and might cover energy and water balances at global scales, validation of general trends and identificiation of drift within model output.

At this stage, the format and method for making these recipes is still in refinement and may be revised many times yet. It is assumed they will be run on model output which is for testing/prototyping only and may not be kept long term.

Some suggestions for writing recipes:
- Use the [access-nri-intake-catalogue](https://github.com/ACCESS-NRI/access-nri-intake-catalog/) if at all possible. For the model output beeing evaluated, you will need to build your own datastore. If you wish to compare against other / previous models, this data should be loaded through the current intake catalogue.
- Develop recipes using _conda/analysis3_ environment from the hh5 project, unless there is a specific need for something different. Including which environment was used for development in the comments is a good idea. (These are instructions [here](https://access-hive.org.au/model_evaluation/model_evaluation_on_gadi/model_evaluation_on_gadi_pangeo_cosima/) for using hh5)
- Consider others reading your recipes by using markup and comments.
- Formatting your recipes through _black_ is good practice

The recipes in this repository are (at this stage) not reviewed.

## COPYRIGHT Header

Best practice suggests adding a copyright statement at the top of every source code file, e.g. for Python:
```python
# Copyright 2022 ACCESS-NRI and contributors. See the top-level COPYRIGHT file for details.
# SPDX-License-Identifier: Apache-2.0
```


## Ocean / Sea Ice

There is a [thread](https://forum.access-hive.org.au/t/access-om3-evaluation/1462) on ACCESS-Hive with the planned / discussed plots for evaluation

## Atmosphere

## Land

## Ice Sheets

