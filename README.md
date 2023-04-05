# Funtions-in-Python
{
  "metadata": {
    "language_info": {
      "codemirror_mode": {
        "name": "python",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.8"
    },
    "kernelspec": {
      "name": "python",
      "display_name": "Pyolite",
      "language": "python"
    }
  },
  "nbformat_minor": 4,
  "nbformat": 4,
  "cells": [
    {
      "cell_type": "markdown",
      "source": "Functions in Python\nEstimated time needed: 40 minutes\n\nObjectives\nAfter completing this lab you will be able to:\n\nUnderstand functions and variables\nWork with functions and variables",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "# First function example: Add 1 to a and store as b\n\ndef add(a):\n    \"\"\"\n    add 1 to a\n    \"\"\"\n    b = a + 1\n    print(a, \"if you add one\", b)\n    return(b)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 4,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Get a help on add function\n\nhelp(add)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 5,
      "outputs": [
        {
          "name": "stdout",
          "text": "Help on function add in module __main__:\n\nadd(a)\n    add 1 to a\n\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Call the function add()\n\nadd(1)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 6,
      "outputs": [
        {
          "name": "stdout",
          "text": "1 if you add one 2\n",
          "output_type": "stream"
        },
        {
          "execution_count": 6,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Call the function add()\n\nadd(2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 7,
      "outputs": [
        {
          "name": "stdout",
          "text": "2 if you add one 3\n",
          "output_type": "stream"
        },
        {
          "execution_count": 7,
          "output_type": "execute_result",
          "data": {
            "text/plain": "3"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Define a function for multiple two numbers\n\ndef Mult(a, b):\n    c = a * b\n    return(c)\n    print('This is not printed')\n    \nresult = Mult(12,2)\nprint(result)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 8,
      "outputs": [
        {
          "name": "stdout",
          "text": "24\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Use mult() multiply two integers\n\nMult(2, 3)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 9,
      "outputs": [
        {
          "execution_count": 9,
          "output_type": "execute_result",
          "data": {
            "text/plain": "6"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Use mult() multiply two floats\n\nMult(10.0, 3.14)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 10,
      "outputs": [
        {
          "execution_count": 10,
          "output_type": "execute_result",
          "data": {
            "text/plain": "31.400000000000002"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Use mult() multiply two different type values together\n\nMult(2, \"Michael Jackson \")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 11,
      "outputs": [
        {
          "execution_count": 11,
          "output_type": "execute_result",
          "data": {
            "text/plain": "'Michael Jackson Michael Jackson '"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Function Definition\n\ndef square(a):\n    \n    # Local variable b\n    b = 1\n    c = a * a + b\n    print(a, \"if you square + 1\", c) \n    return(c)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 12,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Initializes Global variable  \n\nx = 3\n# Makes function call and return function a y\ny = square(x)\ny",
      "metadata": {
        "trusted": true
      },
      "execution_count": 13,
      "outputs": [
        {
          "name": "stdout",
          "text": "3 if you square + 1 10\n",
          "output_type": "stream"
        },
        {
          "execution_count": 13,
          "output_type": "execute_result",
          "data": {
            "text/plain": "10"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Directly enter a number as parameter\n\nsquare(2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 14,
      "outputs": [
        {
          "name": "stdout",
          "text": "2 if you square + 1 5\n",
          "output_type": "stream"
        },
        {
          "execution_count": 14,
          "output_type": "execute_result",
          "data": {
            "text/plain": "5"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Define functions, one with return value None and other without return value\n\ndef MJ():\n    print('Michael Jackson')\n    \ndef MJ1():\n    print('Michael Jackson')\n    return(None)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 15,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# See the output\n\nMJ()",
      "metadata": {
        "trusted": true
      },
      "execution_count": 16,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# See the output\n\nMJ1()",
      "metadata": {
        "trusted": true
      },
      "execution_count": 17,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# See what functions returns are\n\nprint(MJ())\nprint(MJ1())",
      "metadata": {
        "trusted": true
      },
      "execution_count": 18,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson\nNone\nMichael Jackson\nNone\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Define the function for combining strings\n\ndef con(a, b):\n    return(a + b)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 19,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Test on the con() function\n\ncon(\"This \", \"is\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 20,
      "outputs": [
        {
          "execution_count": 20,
          "output_type": "execute_result",
          "data": {
            "text/plain": "'This is'"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# a and b calculation block1\n\na1 = 4\nb1 = 5\nc1 = a1 + b1 + 2 * a1 * b1 - 1\nif(c1 < 0):\n    c1 = 0 \nelse:\n    c1 = 5\nc1   ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 21,
      "outputs": [
        {
          "execution_count": 21,
          "output_type": "execute_result",
          "data": {
            "text/plain": "5"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# a and b calculation block2\n\na2 = 0\nb2 = 0\nc2 = a2 + b2 + 2 * a2 * b2 - 1\nif(c2 < 0):\n    c2 = 0 \nelse:\n    c2 = 5\nc2   ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 22,
      "outputs": [
        {
          "execution_count": 22,
          "output_type": "execute_result",
          "data": {
            "text/plain": "0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Make a Function for the calculation above\n\ndef Equation(a,b):\n    c = a + b + 2 * a * b - 1\n    if(c < 0):\n        c = 0 \n    else:\n        c = 5\n    return(c) ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 23,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "a1 = 4\nb1 = 5\nc1 = Equation(a1, b1)\nc1",
      "metadata": {
        "trusted": true
      },
      "execution_count": 24,
      "outputs": [
        {
          "execution_count": 24,
          "output_type": "execute_result",
          "data": {
            "text/plain": "5"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "a2 = 0\nb2 = 0\nc2 = Equation(a2, b2)\nc2",
      "metadata": {
        "trusted": true
      },
      "execution_count": 25,
      "outputs": [
        {
          "execution_count": 25,
          "output_type": "execute_result",
          "data": {
            "text/plain": "0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Build-in function print()\n\nalbum_ratings = [10.0, 8.5, 9.5, 7.0, 7.0, 9.5, 9.0, 9.5] \nprint(album_ratings)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 26,
      "outputs": [
        {
          "name": "stdout",
          "text": "[10.0, 8.5, 9.5, 7.0, 7.0, 9.5, 9.0, 9.5]\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Use sum() to add every element in a list or tuple together\n\nsum(album_ratings)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 27,
      "outputs": [
        {
          "execution_count": 27,
          "output_type": "execute_result",
          "data": {
            "text/plain": "70.0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Show the length of the list or tuple\n\nlen(album_ratings)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 28,
      "outputs": [
        {
          "execution_count": 28,
          "output_type": "execute_result",
          "data": {
            "text/plain": "8"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Function example\n\ndef type_of_album(artist, album, year_released):\n    \n    print(artist, album, year_released)\n    if year_released > 1980:\n        return \"Modern\"\n    else:\n        return \"Oldie\"\n    \nx = type_of_album(\"Michael Jackson\", \"Thriller\", 1980)\nprint(x)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 29,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson Thriller 1980\nOldie\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the list using for loop\n\ndef PrintList(the_list):\n    for element in the_list:\n        print(element)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 30,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Implement the printlist function\n\nPrintList(['1', 1, 'the man', \"abc\"])",
      "metadata": {
        "trusted": true
      },
      "execution_count": 31,
      "outputs": [
        {
          "name": "stdout",
          "text": "1\n1\nthe man\nabc\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "#Compare Two Strings Directly using in operator\n# add string\nstring= \"Michael Jackson is the best\"\n\n# Define a funtion\ndef check_string(text):\n    \n# Use if else statement and 'in' operatore to compare the string\n    if text in string:\n        return 'String matched'\n    else:\n        return 'String not matched'\n\ncheck_string(\"Michael Jackson is the best\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 32,
      "outputs": [
        {
          "execution_count": 32,
          "output_type": "execute_result",
          "data": {
            "text/plain": "'String matched'"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "#Compare two strings using == operator and function\ndef compareStrings(x, y):\n# Use if else statement to compare x and y\n    if x==y:\n        return 1\n    \n# Declare two different variables as string1 and string2 and pass string in it\nstring1 = \"Michael Jackson is the best\"\nstring2 = \"Michael Jackson is the best\"\n\n# Declare a variable to store result after comparing both the strings\ncheck = compareStrings(string1, string2)\n\n#Use if else statement to compare the string\nif check==1:\n    print(\"\\nString Matched\")\nelse:\n    print(\"\\nString not Matched\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 33,
      "outputs": [
        {
          "name": "stdout",
          "text": "\nString Matched\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Python Program to Count words in a String using Dictionary\ndef freq(string):\n    \n    #step1: A list variable is declared and initialized to an empty list.\n    words = []\n    \n    #step2: Break the string into list of words\n    words = string.split() # or string.lower().split()\n    \n    #step3: Declare a dictionary\n    Dict = {}\n    \n    #step4: Use for loop to iterate words and values to the dictionary\n    for key in words:\n        Dict[key] = words.count(key)\n        \n    #step5: Print the dictionary\n    print(\"The Frequency of words is:\",Dict)\n    \n#step6: Call function and pass string in it\nfreq(\"Mary had a little lamb Little lamb, little lamb Mary had a little lamb.Its fleece was white as snow And everywhere that Mary went Mary went, Mary went \\\nEverywhere that Mary went The lamb was sure to go\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 34,
      "outputs": [
        {
          "name": "stdout",
          "text": "The Frequency of words is: {'Mary': 6, 'had': 2, 'a': 2, 'little': 3, 'lamb': 3, 'Little': 1, 'lamb,': 1, 'lamb.Its': 1, 'fleece': 1, 'was': 2, 'white': 1, 'as': 1, 'snow': 1, 'And': 1, 'everywhere': 1, 'that': 2, 'went': 3, 'went,': 1, 'Everywhere': 1, 'The': 1, 'sure': 1, 'to': 1, 'go': 1}\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Example for setting param with default value\n\ndef isGoodRating(rating=4): \n    if(rating < 7):\n        print(\"this album sucks it's rating is\",rating)\n        \n    else:\n        print(\"this album is good its rating is\",rating)\n",
      "metadata": {
        "trusted": true
      },
      "execution_count": 35,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Test the value with default value and with input\n\nisGoodRating()\nisGoodRating(10)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 36,
      "outputs": [
        {
          "name": "stdout",
          "text": "this album sucks it's rating is 4\nthis album is good its rating is 10\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Example of global variable\n\nartist = \"Michael Jackson\"\ndef printer1(artist):\n    internal_var1 = artist\n    print(artist, \"is an artist\")\n    \nprinter1(artist)\n# try runningthe following code\n#printer1(internal_var1) ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 37,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson is an artist\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "artist = \"Michael Jackson\"\n\ndef printer(artist):\n    global internal_var \n    internal_var= \"Whitney Houston\"\n    print(artist,\"is an artist\")\n\nprinter(artist) \nprinter(internal_var)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 38,
      "outputs": [
        {
          "name": "stdout",
          "text": "Michael Jackson is an artist\nWhitney Houston is an artist\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Example of global variable\n\nmyFavouriteBand = \"AC/DC\"\n\ndef getBandRating(bandname):\n    if bandname == myFavouriteBand:\n        return 10.0\n    else:\n        return 0.0\n\nprint(\"AC/DC's rating is:\", getBandRating(\"AC/DC\"))\nprint(\"Deep Purple's rating is:\",getBandRating(\"Deep Purple\"))\nprint(\"My favourite band is:\", myFavouriteBand)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 39,
      "outputs": [
        {
          "name": "stdout",
          "text": "AC/DC's rating is: 10.0\nDeep Purple's rating is: 0.0\nMy favourite band is: AC/DC\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Deleting the variable \"myFavouriteBand\" from the previous example to demonstrate an example of a local variable \n\ndel myFavouriteBand\n\n# Example of local variable\n\ndef getBandRating(bandname):\n    myFavouriteBand = \"AC/DC\"\n    if bandname == myFavouriteBand:\n        return 10.0\n    else:\n        return 0.0\n\nprint(\"AC/DC's rating is: \", getBandRating(\"AC/DC\"))\nprint(\"Deep Purple's rating is: \", getBandRating(\"Deep Purple\"))\nprint(\"My favourite band is\", myFavouriteBand)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 40,
      "outputs": [
        {
          "name": "stdout",
          "text": "AC/DC's rating is:  10.0\nDeep Purple's rating is:  0.0\n",
          "output_type": "stream"
        },
        {
          "ename": "<class 'NameError'>",
          "evalue": "name 'myFavouriteBand' is not defined",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "Cell \u001b[0;32mIn[40], line 16\u001b[0m\n\u001b[1;32m     14\u001b[0m \u001b[38;5;28mprint\u001b[39m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mAC/DC\u001b[39m\u001b[38;5;124m'\u001b[39m\u001b[38;5;124ms rating is: \u001b[39m\u001b[38;5;124m\"\u001b[39m, getBandRating(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mAC/DC\u001b[39m\u001b[38;5;124m\"\u001b[39m))\n\u001b[1;32m     15\u001b[0m \u001b[38;5;28mprint\u001b[39m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mDeep Purple\u001b[39m\u001b[38;5;124m'\u001b[39m\u001b[38;5;124ms rating is: \u001b[39m\u001b[38;5;124m\"\u001b[39m, getBandRating(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mDeep Purple\u001b[39m\u001b[38;5;124m\"\u001b[39m))\n\u001b[0;32m---> 16\u001b[0m \u001b[38;5;28mprint\u001b[39m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mMy favourite band is\u001b[39m\u001b[38;5;124m\"\u001b[39m, \u001b[43mmyFavouriteBand\u001b[49m)\n",
            "\u001b[0;31mNameError\u001b[0m: name 'myFavouriteBand' is not defined"
          ],
          "output_type": "error"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Example of global variable and local variable with the same name\n\nmyFavouriteBand = \"AC/DC\"\n\ndef getBandRating(bandname):\n    myFavouriteBand = \"Deep Purple\"\n    if bandname == myFavouriteBand:\n        return 10.0\n    else:\n        return 0.0\n\nprint(\"AC/DC's rating is:\",getBandRating(\"AC/DC\"))\nprint(\"Deep Purple's rating is: \",getBandRating(\"Deep Purple\"))\nprint(\"My favourite band is:\",myFavouriteBand)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 41,
      "outputs": [
        {
          "name": "stdout",
          "text": "AC/DC's rating is: 0.0\nDeep Purple's rating is:  10.0\nMy favourite band is: AC/DC\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "def printAll(*args): # All the arguments are 'packed' into args which can be treated like a tuple\n    print(\"No of arguments:\", len(args)) \n    for argument in args:\n        print(argument)\n#printAll with 3 arguments\nprintAll('Horsefeather','Adonis','Bone')\n#printAll with 4 arguments\nprintAll('Sidecar','Long Island','Mudslide','Carriage')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 42,
      "outputs": [
        {
          "name": "stdout",
          "text": "No of arguments: 3\nHorsefeather\nAdonis\nBone\nNo of arguments: 4\nSidecar\nLong Island\nMudslide\nCarriage\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "def printDictionary(**args):\n    for key in args:\n        print(key + \" : \" + args[key])\n\nprintDictionary(Country='Canada',Province='Ontario',City='Toronto')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 43,
      "outputs": [
        {
          "name": "stdout",
          "text": "Country : Canada\nProvince : Ontario\nCity : Toronto\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "def addItems(list):\n    list.append(\"Three\")\n    list.append(\"Four\")\n\nmyList = [\"One\",\"Two\"]\n\naddItems(myList)\n\nmyList\n    ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 44,
      "outputs": [
        {
          "execution_count": 44,
          "output_type": "execute_result",
          "data": {
            "text/plain": "['One', 'Two', 'Three', 'Four']"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Come up with a function that divides the first input by the second input:\ndef div(a, b):\n    return(a/b)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 46,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Use the function con for the following question.\ndef con(a, b):\n    return(a + b)",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Can the con function we defined before be used to add two integers or strings?\n## Yes, for example: \ncon(2, 2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 49,
      "outputs": [
        {
          "execution_count": 49,
          "output_type": "execute_result",
          "data": {
            "text/plain": "4"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Can the con function we defined before be used to concatenate lists or tuples?\n##Yes, for example: \ncon(['a', 1], ['b', 1])",
      "metadata": {
        "trusted": true
      },
      "execution_count": 50,
      "outputs": [
        {
          "execution_count": 50,
          "output_type": "execute_result",
          "data": {
            "text/plain": "['a', 1, 'b', 1]"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Write a function code to find total count of word little in the given string: \"Mary had a little lamb Little lamb, little lamb Mary had a little lamb.Its fleece was white as snow And everywhere that Mary went Mary went, Mary went Everywhere that Mary went The lamb was sure to go\"**\n\ndef freq(string,passedkey):\n\n    #step1: A list variable is declared and initialized to an empty list.\n    words = []\n\n    #step2: Break the string into list of words\n    words = string.split() # or string.lower().split()\n\n    #step3: Declare a dictionary\n    Dict = {}\n\n    #step4: Use for loop to iterate words and values to the dictionary\n    for key in words:\n        if(key == passedkey):\n            Dict[key] = words.count(key)   \n    #step5: Print the dictionary\n    print(\"Total Count:\",Dict)\n\n#step6: Call function and pass string in it\nfreq(\"Mary had a little lamb Little lamb, little lamb Mary had a little lamb.Its fleece was white as snow And everywhere that Mary went Mary went, Mary went \\\nEverywhere that Mary went The lamb was sure to go\",\"little\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 51,
      "outputs": [
        {
          "name": "stdout",
          "text": "Total Count: {'little': 3}\n",
          "output_type": "stream"
        }
      ]
    }
  ]
}
