# Family-History
For this Page I'm just going to be talking about my family and their history

## Countries
> My family are born and raised in [El Salvador](https://en.wikipedia.org/wiki/El_Salvador) but they left their homes to search for a better life here in America. They actually all have citizenships or residencies so they are allowed to work and live here.
> Me and my sister were born here along with some of my cousins so we sometimes don't face the troubles that our parents sometimes went through.

### Parents
> My parents moved to the US when they were still teenagers and they both met a few years later in Virginia.
> My dad was born in a [farming](https://en.wikipedia.org/wiki/Sensuntepeque) community along with my uncle and 3 aunts.
> My mom was actually born on an [island](https://www.elsalvadormipais.com/wp-content/uploads/2017/01/isla-la-pirraya.jpg) was nearby the cost of the Usulutan port with my uncle and half aunt.

## The Reasons
> I do not know the full reason why they left the country they lived their whole lives in but during the time they were living their, poverty was a big thing there due to corruption in the government and also the gang activities there were as well.
![El Salvador](https://cdn.britannica.com/s:300x169,c:crop/31/7231-050-E0D5C157/El-Salvador-map-features-locator.jpg)

>As you can see in the image its the smallest country in the Central American and Carribean area which isn't so great since in the past there were wars with Guatemala and Honduras. Other countries in Central America are:
* Panama
* Nicaragua 
* Costa Rica
* Belize

# Random Code
>This is a code that I did that will read a file but has to have a writer code and write down a file before running this reader code.

def displayNumbers(fileToBeRead):
    
    randomNumbersFile = open(fileToBeRead, "r")

    total=0
    numberOfRandomNumbers = 0
    line = randomNumbersFile.readline()

    while line != "":
        numberOfRandomNumbers +=1
        randomNumber = int(line)
        total += randomNumber
        print(randomNumber)
        line = randomNumbersFile.readline()
    print("The total of all numbers in the file is " + str(total) +\
          "\nThere are " + str(numberOfRandomNumbers) + \
          " numbers in the file")
def main():
        
        displayNumbers("randomNumbers.txt")
main()
