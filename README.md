![Python](https://miro.medium.com/max/1400/1*HacaJfdu7HF8V4gIoA98ww.png)

# Introduction to Python Programming language

> What is Python ?

> How To Setup On Linux

> Python courses

> Intelligent assistant to learn Python

## What is Python ?

Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant whitespace. 

## What is difference between Python 2 and Python 3?

| Basis of comparison	 | Python 3	          | Python 2      |
| :---:                |     :---:          |          :---: |
| Function print       | print ("hello")	  | print "hello" |
| Division of Integers | Whenever two integers are divided, you get a float value	 | When two integers are divided, you always provide integer value |
| Unicode              |     In Python 3, default storing of strings is Unicode    | To store Unicode string value, you require to define them with "u"  |
| Syntax               |     The syntax is simpler and easily understandable       | The syntax of Python 2 was comparatively difficult to understand      |
| Rules of ordering Comparisons  |     In this version, Rules of ordering comparisons have been simplified  |  Rules of ordering comparison are very complex |
| Iteration            |  The new Range() function introduced to perform iterations |  In Python 2, the xrange() is used for iterations |
| Exceptions           |     It should be enclosed in parenthesis          |          It should be enclosed in notations |
| Leak of variables    |     The value of variables never changes          |          The value of the global variable will change while using it inside for-loop |
| Backward compatibility                |     Not difficult to port python 2 to python 3 but it is never reliable          |          Python version 3 is not backwardly compatible with Python 2 |
| Library                |     Many recent developers are creating libraries which you can only use with Python 3          |          Many recent developers are creating libraries which you can only use with Python 3.	Many older libraries created for Python 2 is not forward-compatible |

## Python 2 vs. Python 3 Example Code

> Python 3

```
// Python3.X

def main():
  print("Hello World!")
  
if __name__== "__main__":
  main()
```
> Python2 

```
// Python2.X

def main():
  print "Hello World!"
  
if __name__== "__main__":
  main()
```

## Which Python Version to Use?

When it comes to Python version 2 vs. 3 today, Python 3 is the outright winner. That's because Python 2 won't be available after 2020. Mass Python 3 adoption is the clear direction of the future.

After considering declining support for Python 2 programming language and added benefits from upgrades to Python 3, it is always advisable for a new developer to select Python version 3. However, if a job demands Python 2 capabilities, that would be an only compelling reason to use this version.

## KEY DIFFERENCE

* Python 3 syntax is simpler and easily understandable whereas Python 2 syntax is comparatively difficult to understand.
* Python 3 default storing of strings is Unicode whereas Python 2 stores need to define Unicode string value with "u."
* Python 3 value of variables never changes whereas in Python 2 value of the global variable will be changed while using it inside for-loop.
* Python 3 exceptions should be enclosed in parenthesis while Python 2 exceptions should be enclosed in notations.
* Python 3 rules of ordering comparisons are simplified whereas Python 2 rules of ordering comparison are complex.
* Python 3 offers Range() function to perform iterations whereas, In Python 2, the xrange() is used for iterations.

## How To Setup On Linux

Run the following commands as root or user with sudo access to update the packages list and install the prerequisites:

```
// Run

sudo apt update
sudo apt install software-properties-common

```

Add the deadsnakes PPA to your system’s sources list:

```
// Run

sudo add-apt-repository ppa:deadsnakes/ppa

```
When prompted press Enter to continue:

```
// Run
Press [ENTER] to continue or Ctrl-c to cancel adding it.

```
Once the repository is enabled, install Python 3.8 with:

```
// Run
sudo apt install python3.8

```

Verify that the installation was successful by typing:

```
// Run
python3.8 --version
Python 3.8.0


```

At this point, Python 3.8 is installed on your Ubuntu system, and you can start using it.
