# Machine Learning in Finance
Create structured financial data in the form of tick, volume, and dollar bars from unstructured tick data. From Marcos Lopez de Prado's Advances in Financial Machine Learning textbook.

## Getting Started

For running this repository follow below steps for getting started in Windows -

1: install cython by running conda install -c anaconda cython in Anaconda prompt 
2: go in C:\Users\Utilisateur\Anaconda3\Lib\distutils or wherever your distutils library is the create a distutils.cfg file (by using the notepad) and put 
[build]           
compiler=mingw32 
in it 
3: get the latest version of Mingw-w64 (not just Mingw which support just 32 bits) at https://sourceforge.net/projects/mingw-w64/files/ and install it
4: add C:\Program Files (x86)\mingw-w64\i686-8.1.0-posix-dwarf-rt_v6-rev0\mingw32\bin to your Path here is a link on how to do that on windows 10: https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/
5: install libpython and m2w64-toolchain in your anaconda envirement by running conda install -c anaconda libpython and conda install -c msys2 m2w64-toolchain It come from these webpage https://python-at-risoe.pages.windenergy.dtu.dk/compiling-on-windows/common_errors.html and should correct the corresponding errors

### Prerequisites

Ananconda
Cython

### Installing

Install below libraries

conda install -c anaconda statsmodels
pip install seaborn
pip install cython
pip install pandas
pip install python


## Built With

Anaconda
Jupyter Notebook

## Contributing


## Versioning

Original version 10th September 2019

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

https://github.com/Jackal08

