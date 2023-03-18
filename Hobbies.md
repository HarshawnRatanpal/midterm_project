# Hobbies and Interests

## Music
I love listening hip-hop. Below is a list of my favorite rappers and my top three songs from each of them

- **Kendrick Lamar**
    - *Mortal Man*
    - *Mirror*
    - *Prayer*
- **Nas**
    - *Death Row East*
    - *The World is Yours*
    - *Legit*
- **J. Cole**
    - *4 Your Eyez Only*
    - *False Prophets*
    - *Apparently*

## Reading
Over the last couple of months, I've rediscovered a love of reading. Here are some of the books I've read recently,
ranked in order by how much I liked them.
1. *Siddhartha* by Herman Hesse
2. *The Antropocene Reviewed* by John Greene
3. *Born Standing Up* by Steve Martin
4. *Trigger Warning* by Neil Gaiman
5. *The Four Agreements* by Don Miguel Ruiz

## Math and Coding
Through taking this IT class, I've been able to learn much more about coding then I knew before. One of favorite assignments was the below Python
assignment from earlier in the semster, where the volume of various 3D shapes could be calculated. 

<pre>

print("Calculating the Volume of a Cube, Cylinder or Cone: ")
import math

print ("Choose an option below ")
print ("1. Cube")
print ("2. Cylinder")
print ("3. Cone")

shape = input('Please enter 1 for Cube, 2 for Cylidner, or 3 for Cone ')

def cube():
        length = float(input(' Enter the length of your Cube: '))
        Volume = length * length * length
        print(" The Volume of a Cube = %f" %Volume)


def cylinder():
        radius = float(input(' Enter the Radius of your Cylinder: '))
        height = float(input(' Enter the Height of ypur Cylinder: '))
        Volume = math.pi * radius * radius * height
        print(" The Volume of a Cylinder = %f" %Volume)


def cone():
        radius = float(input(' Enter the Radius of your Cone: '))
        height = float(input(' Enter the Height of ypur Cone: '))
        Volume = (1/3) * math.pi * radius * radius * height
        print(" The Volume of a Cone = %f" %Volume)


if (shape == "1"):
    total = cube()
    
if (shape == "2"):
    total = cylinder()
    
if (shape == "3"):
    total = cone()

</pre>
***
[Previous](AboutMe.md)
*** 
#### Learn all about Harshawn by using this site navigator!
* [Home](README.md)
* [Work and Education](Work.md)
* [Contact Me](Contact.md)
* [About Me](AboutMe.md)
* [Hobbies and Interests](Hobbies.md)
