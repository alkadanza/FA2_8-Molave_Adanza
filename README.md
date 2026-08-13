# distance of two points

## Description
- The program first asks the user for the coordinates of two points and then the code calculates the distance of the two points and shows the output.

## How to Run
1. Open the program.
2. Run the program.
3. Enter the required values.

## Input Needed
- x1
- x2
- y1
- y2

## Sample Output
import math

Get coordinates from the user
def get_coordinate(label):
    return float(input(f"Enter {label}: "))

Calculate the distance between two points
def calculate_distance(p1, p2):
    x1, y1 = p1
    x2, y2 = p2

    # Distance formula
    return math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

def main():
    print("=== Distance Calculator ===")

    # Get the coordinates
    x2 = get_coordinate("x2")
    x1 = get_coordinate("x1")
    y2 = get_coordinate("y2")
    y1 = get_coordinate("y1")

    # Create the two points
    point1 = (x1, y1)
    point2 = (x2, y2)

    # Calculate and display the distance
    distance = calculate_distance(point1, point2)
    print(f"\nDistance: {distance:.2f} units")

if _name_ == "_main_":
    main()


## Author
Name: Alyssa Kaitlyn D. Adanza
Section: 8- Molave
