# pressure-formula
def calculate_pressure(force, area):
    """Calculate pressure given force and area."""
    if area <= 0:
        return "Area must be greater than zero!"
    return force / area

# Example usage
force = 500  # Newtons
area = 2  # Square meters
pressure = calculate_pressure(force, area)
print(f"Pressure: {pressure} Pascals (N/m²)")
dare
hui
