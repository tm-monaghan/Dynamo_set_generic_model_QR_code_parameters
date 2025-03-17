# dynamo_set_generic_model_QR_code_parameters
This is a Revit Dynamo script which sets the parameters of a three dimensional generic model QR code element.<br>
The QR code element can be used to tag spaces or elements within Revit.<br>
The script uses the ["pyQRcode"](https://pythonhosted.org/PyQRCode/) library to convert a text string to an Ascii stream of ones and zeros, which is then used to configure the materials on a Revit Generic Model Component.<br>
[A revit file, hosting the QR code Generic Model Component is provided in the repository.](https://github.com/tm-monaghan/Dynamo_set_generic_model_QR_code_parameters/blob/main/Revit_QR_code_host_file.rvt)
