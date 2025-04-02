# medtronic-tracts-extractor

Medtronic Stealth Station is a surgical navigation system in which an operator can precisely track the location of surgical instruments throughout a surgical procedure.
It can be expanded with a software module to perform expert-assisted tractography in the brain, to help with surgical planning.

After preparing a patient for treatment with the Stealth Station system, i.e. importing all relevant MRI and DTI scans of the patient and carrying out tractography, the complete record of the patient can be exported from the Steath Station as a Dicom file that contains a single raw binary image.

This web-app takes the exported DICOM image (drag/drop on the page) and extracts the data files from it, in particular the ones containing fiber tracts. 
