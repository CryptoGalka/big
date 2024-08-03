# big
def count_big_plants(plant_list):
    # Define what constitutes a 'big' plant, for example, using a keyword in the plant name
    big_plant_keyword = 'Big'
    return sum(big_plant_keyword in plant for plant in plant_list)

# Example usage
plants = ['Big Rose', 'Small Tulip', 'Big Daisy', 'Medium Tulip', 'Big Oak']
big_plant_count = count_big_plants(plants)
print(f'Number of big plants: {big_plant_count}')
