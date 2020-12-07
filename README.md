# helm-repo

Repository for helm charts used for Sledilnik deployments. Charts are located in folder charts (on brainc `master`).

## Charts

### data-api

Chart for deployment of [data-api](https://www.github.com/sledilnik/data-api)

### django

general chart for django app deployment, currently used for [website-backend](https://www.github.com/sledilnik/website-backend)

### website

Chart for deployment of [website](https://www.github.com/sledilnik/website). 

### spark

Chart for deployment of [spark](https://www.github.com/sledilnik/spark)

## Development notes

When you make changes to chart, be sure to bump `version` field in `Chart.yaml`, othewrise job that releases charts will fail (attempt to override existing release will fail).

## TODO

* Charts `website` and `spark` are almost the same and could be probably merged into one general chart for deployment of static sites.
