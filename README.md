# test-plans
YAML Test Plans for the PLT
This should include example test plans. Do not put confidential files in here.
We could consider making this a public repo in the future.

## Authoring

Start new plans from `TEMPLATE.yaml`. Every plan carries a header with a
Test Station BOM and a Test Station Diagram (TSD). The TSD uses the standard
five-column wiring format, one row per cable:

    Device A | Connector | Cable P/N | Connector | Device B
