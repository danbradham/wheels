# wheels
Prebuilt wheels for strange Python builds!

# Why do these wheels exist?
DCC Software like Autodesk Maya, Maxon Cinema4d, and Blender all include their own python interpreters. On Windows the software developers build their included python interpreter with the same version of Microsoft Visual Studio they used to build their applications. Unfortunately the version of Microsoft Visual Studio they use does not always match the official builds of python you'd download from python.org. This mismatch of the build environment makes it impossible to use prebuilt wheels from pypi within the DCC. This is especially true for a complex library like Qt.
