# Timed Math Quiz Game

This is a simple timed mathematical quiz game implemented in Golang. The quiz runs for a default time of 30 seconds and uses a default CSV file (`problems.csv`) to extract mathematical problems. 

## Features
- **Timed Quiz:** The quiz runs with a default timer of 30 seconds.
- **CSV Input:** It takes a CSV file (`problems.csv`) as input which contains the math problems.
- **Score Calculation:** It checks if the answers provided are correct and calculates the score.
- **Immediate Feedback:** The quiz ends as soon as the timer runs out, displaying the number of correct answers.

## Getting Started

### Prerequisites
- Go (Golang) installed on your machine. You can download it from [here](https://golang.org/dl/).

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/quiz-game-timed.git
    ```
2. Navigate to the project directory:
    ```sh
    cd quiz-game-timed
    ```

### Usage
1. Ensure you have a `problems.csv` file in the same directory as `main.go`. The file should be formatted as follows:
    ```csv
    question,answer
    5+5,10
    1+1,2
    8+3,11
    1+2,3
    8+6,14
    ...
    ```

2. Run the quiz:
    ```sh
    go run main.go
    ```

3. You will see questions being displayed one by one. Answer them within the time limit. The quiz will end automatically after 30 seconds, displaying your score.

### Example

The `problems.csv` file:

```csv
question,answer
5+5,10
1+1,2
8+3,11
1+2,3
8+6,14
3+1,4
1+4,5
5+1,6
2+3,5
3+3,6
2+4,6
5+2,7
10+2,12
