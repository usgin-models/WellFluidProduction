This repository contains document artifacts for an information exchange for well fluid production observations. The artifacts include an Excel Workbook that defines and documents the content model, and an XML schema that implements the model.

The Excel workbook documents a content model for exchange of information about fluid production for a given well. A generic  model is intended to allow for  a variety of flows from a well including oil, gas, and water as well as steam production. Because of the wide variety of possible flow measurements (commodities, aggregation type), the model adopts a thin approach, which may result in many records being returned for a single well. Thus most data about the well is linked through the HeaderURI instead of included inline to keep the redundant data volume down.

Services are not yet deployed using this information exchange.
