..
  SPDX-License-Identifier: BSD-3-Clause
  Copyright Contributors to the OpenEXR Project.

Chromaticities
##############

Four OpenEXR files that can be used to test if a program that displays
images handles the files' chromaticities attribute correctly.

Displayed properly, all four images should look the same.

.. list-table::
   :align: left
   
   * - ``Rec709.exr``

     - R, G, B channels with chromaticities according to Rec. ITU-R BT.709-3

   * - ``Rec709_YC.exr``

     - Luminance/chroma encoded image, generated from R, G, B channels
       with chromaticities according to Rec. ITU-R BT.709-3

   * - ``XYZ.exr``

     - R, G, B channels with chromaticities such that R, G and B
       correspond to CIE X, Y and Z

   * - ``XYZ_YC.exr``

     - Luminance/chroma encoded image, generated from R, G, B channels
       with chromaticities such that R, G and B correspond to CIE X, Y
       and Z

