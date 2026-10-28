import csv
def weather_reader():
    city = input("Please enter a city: ")
    month = input("Please enter a month: ")
    with open("weather_temps (3).csv", "r") as table:
        table = csv.reader(table)
        for row in table:
            if row[0] == city and row[1] == month:
                print(f"Average high temperature in {city} during {month} is {row[2]}")
                print(f"Average low temperature in {city} during {month} is {row[3]}")

if __name__ == '__main__':
    weather_reader()

