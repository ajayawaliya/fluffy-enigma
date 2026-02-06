# fluffy-enigma

from config import APP_NAME, VERSION
from utils import add, subtract, multiply, divide
from logger import logger

def main():
    logger.info(f"Starting {APP_NAME} v{VERSION}")

    a, b = 10, 5
    logger.info(f"Add: {add(a, b)}")
    logger.info(f"Subtract: {subtract(a, b)}")
    logger.info(f"Multiply: {multiply(a, b)}")
    logger.info(f"Divide: {divide(a, b)}")

if __name__ == "__main__":
    main()
