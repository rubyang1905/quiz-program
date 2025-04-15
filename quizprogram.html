# quiz-program
import java.util.HashMap;
import java.util.Scanner;

public class QuizProgram {

    private static HashMap<String, String> users = new HashMap<>();

    public static void main(String[] args) {
        Scanner quiz = new Scanner(System.in);
        
        String choice;

        users.put("testUser", "password123");

        while (true) {
            System.out.println("\n=== Quiz Program ===");
            System.out.println("1. Log In");
            System.out.println("2. Register");
            System.out.println("3. Exit");
            System.out.print("Enter Your Choice: ");
            choice = quiz.nextLine();

            if (choice.equals("3")) {
                System.out.println("\nExiting the Quiz. Thank You for Participating. Goodbye!\n");
                break;
            } else if (choice.equals("1")) {
                if (logIn(quiz)) {
                    startQuiz(quiz);
                }
            } else if (choice.equals("2")) {
                register(quiz);
            } else {
                System.out.println("\nInvalid Choice. Please Enter 1 to Log In, 2 to Register, or 3 to Exit.");
            }
        }

        quiz.close();
    }

    private static boolean logIn(Scanner login) {
        System.out.println("\n=== Log In ===");
        System.out.print("Enter Username: ");
        String username = login.nextLine();
        System.out.print("Enter Password: ");
        String password = login.nextLine();

        if (users.containsKey(username) && users.get(username).equals(password)) {
            System.out.println("Log In Successful! Welcome '" + username + "'!\n");
            return true;
        } else {
            System.out.println("Invalid Username or Password. Please Try Again.");
            return false;
        }
    }

    private static void register(Scanner regi) {
        System.out.println("\n=== Register ===");
        System.out.print("Enter a Username: ");
        String username = regi.nextLine();

        if (users.containsKey(username)) {
            System.out.println("Username Already Taken. Please Choose Another One.");
        } else {
            System.out.print("Enter a Password: ");
            String password = regi.nextLine();
            users.put(username, password);
            System.out.println("\nRegistered Successfully! You Can Now Log In With Your New Account.\n");
            System.out.println("Account Created For '" + username + "'. You Can Now Log In With Your USERNAME And PASSWORD.");
        }
    }

    private static void startQuiz(Scanner start) {
        int score = 0;
        String difficulty;

        while (true) {
            System.out.println("\n=== Quiz Program ===");
            System.out.println("1. Start Quiz");
            System.out.println("2. Log Out");
            System.out.print("Enter your choice: ");
            String choice = start.nextLine();

            if (choice.equals("2")) {
                System.out.println("\nLogging out...\n");
                break;
            } else if (choice.equals("1")) {
                System.out.println("\nSelect Difficulty Level:");
                System.out.println("1. Easy");
                System.out.println("2. Moderate");
                System.out.println("3. Hard");
                System.out.print("Enter your choice: ");
                difficulty = start.nextLine();

                if (!difficulty.equals("1") && !difficulty.equals("2") && !difficulty.equals("3")) {
                    System.out.println("\nInvalid Difficulty Choice. Returning to the Main Menu...");
                    continue;
                }

                score = 0;
                String[][] questions;
                String[] userAnswers;

                if (difficulty.equals("1")) {
                    questions = new String[][] {
                        {"1. What is the size of a char in Java?\n", "Byte", "2 Bytes", "4 Bytes", "8 Bytes\n", "B"},
                        {"2. Which method is used to print text in Java?\n", "Console.write()", "System.out.println", "print.out", "System.writeText()\n", "B"}
                    };
                } else if (difficulty.equals("2")) {
                    questions = new String[][] {
                        {"1. Which of the following is not wrapper class?\n", "Integer", "Character", "String", "Boolean\n", "C"},
                        {"2. Which statement is used to exit a loop?\n", "continue", "break", "return", "exit\n", "B"}
                    };
                } else {
                    questions = new String[][] {
                        {"1. What is the default value of a reference variable in Java?\n", "null", "0", "''", "undefined\n", "A"},
                        {"2. Which class is used for atomic operations in Java?\n", "AtomicReference", "AtomicInteger", "AtomicBoolean", "All of the Above\n", "D"}
                    };
                }

                userAnswers = new String[questions.length];
                System.out.println("\nStarting Quiz...\n");

                for (int i = 0; i < questions.length; i++) {
                    userAnswers[i] = askQuestion(start, questions[i][0], questions[i][5], questions[i][1], questions[i][2], questions[i][3], questions[i][4]);

                    if (userAnswers[i].equalsIgnoreCase(questions[i][5])) {
                        score++;
                    }
                }

                System.out.println("\nQuiz Completed!");
                System.out.println("Your Final Score: " + score + "/" + questions.length);
                System.out.println("\nReview of Your Answers:");
                for (int i = 0; i < questions.length; i++) {
                    System.out.println("\nQ: " + questions[i][0]);
                    System.out.println("Your Answer: " + userAnswers[i]);
                    if (userAnswers[i].equalsIgnoreCase(questions[i][5])) {
                        System.out.println("Correct! The correct answer was: " + questions[i][questions[i].length - 1]);
                    } else {
                        System.out.println("Wrong! The correct answer was: " + questions[i][5]);
                    }
                }

                // After quiz completion, simply prompt user to return to main menu without extra input.
                System.out.println("\nPress Enter to Return to the Main Menu...");
                start.nextLine(); // This wait is here to make sure the user sees the results before returning to the menu.
            } else {
                System.out.println("\nInvalid Choice. Please Enter 1 to Start or 2 to Log Out.");
            }
        }
    }

    private static String askQuestion(Scanner quest, String question, String correctAnswer, String... options) {
        System.out.println(question);
        for (int i = 0; i < options.length; i++) {
            System.out.println((char) ('A' + i) + ". " + options[i]);
        }

        String answer = getAnswer(quest);
        return answer;
    }

    private static String getAnswer(Scanner ans) {
        String answer;
        while (true) {
            System.out.print("Please Put your Answer Here: ");
            answer = ans.nextLine();
            if (!answer.matches("[a-dA-D]")) {
                System.out.println("\nInvalid Input. Please Enter a Letter (A, B, C, or D). Try Again.");
            } else {
                break;
            }
        }
        return answer;
    }
}
