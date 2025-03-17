# dynamo_set_generic_model_QR_code_parameters
This is a Revit Dynamo script which sets the parameters of a three dimensional generic model QR code element. The QR code element can be used to tag spaces or elements within Revit.
The script uses the "pyQRcode" library to convert a text string to an Ascii stream of ones and zeros, which is then used to configure the materials on a Revit Generic Model Component.
A revit file, hosting the QR code Generic Model Component is prvided in the repository.
