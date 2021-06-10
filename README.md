# wheels
Prebuilt wheels for strange Python builds!

# Why do these wheels exist?
DCC Software like Autodesk Maya, Maxon Cinema4d, and Blender all include their own Python interpreters. On Windows the software developers build their included Python interpreter with the same version of Microsoft Visual Studio they used to build their applications. Unfortunately the version of Microsoft Visual Studio they use doesn't always match the official Python builds you'd download from python.org. This mismatch of build environments makes it impossible to use prebuilt wheels from pypi within the DCC. This is especially true for complex libraries like Qt.
