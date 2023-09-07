Logarithmic Derivation Module of Hyperplane arrangement
==================
By Junyan CHU and Shizuo KAJI

JC was supported by the China Scholarship Council.

# Usage

It is based on [SageMath](https://www.sagemath.org/).
You can either install SageMath locally on your computer or use an online service [CoCalc](https://cocalc.com/).

Open the jupter-notebook named _LogarithmicVectorFieldsOfArrangements.ipynb_ and follow the instruction in the file.
The single file contains both function definitions and some examples.

The basic usage is

    A=HyperPlaneArr([[1,0,0],[0,1,0],[0,0,1],[1,1,1]])
    print(gendic(A.minimal_generators))
    print(A.free_resolution())
    A.plot_vfield(A.minimal_generators[1],xlim=(-2,2),ylim=(-2,2))

Look at Example section in the notebook for details.

# References

- Junyan Chu, _Degrees of logarithmic derivations for a free arrangement minus two hyperplanes_, in preparation



