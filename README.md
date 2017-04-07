# Basic-Arithmetic-Quiz
Arithmetic quiz that grades and tallys score upon completion. 

package basicarithmeticquiz;
import java.util.Scanner;

/**
 *
 * @author Max Peterson
 */
public class BasicArithmeticQuiz {

    
public static void main(String[] args) {
 int answer1, answer2, answer3, answer4, answer5, userAnswer1, userAnswer2, userAnswer3, userAnswer4, userAnswer5, correct1, correct2, correct3, correct4, correct5, testScore;
 Scanner in = new Scanner (System.in);

// question1
System.out.println ("Question 1: What is the sum of 4+6?");
answer1 = 4+6;
userAnswer1 = in.nextInt();

// question2
System.out.println ("Question 2: What is the difference of 7 and 9?");
answer2 = 7-9;
userAnswer2= in.nextInt();

// question3
System.out.println ("Question 3: What is 2785 times 0?");
answer3 = 2785 * 0;
userAnswer3 = in.nextInt();

//question4
System.out.println ("Question 4: What is the quotient of 10 and 5?");
answer4 = 10/5;
userAnswer4 = in.nextInt();

//question5
System.out.println ("Question 5: What is the mean of 10, 8, 9 and 5?");
answer5 = (10+8+9+5)/4;
userAnswer5 = in.nextInt();

System.out.println ("You input " + userAnswer1 + " for question 1. The correct answer is " + answer1 + ".");
System.out.println ("You input " + userAnswer2 + " for question 2. The correct answer is " + answer2 +".");
System.out.println ("You input " + userAnswer3 + " for question 3. The correct answer is " + answer3 + ".");
System.out.println ("You input " + userAnswer4 + " for question 4. The correct answer is " + answer4 + ".");
System.out.println ("You input " + userAnswer5 + " for question 5. The correct answer is " + answer5 +".");
System.out.println();

if (userAnswer1 == answer1)
{
    correct1 =1;
}
else 
{
 correct1 = 0;   
}

if (userAnswer2 == answer2)
{
    correct2 =1;
}
else 
{
 correct2 = 0;   
}

if (userAnswer3 == answer3)
{
    correct3 =1;
}
else 
{
 correct3 = 0;   
}

if (userAnswer4 == answer4)
{
    correct4 =1;
}
else 
{
 correct4 = 0;   
}

if (userAnswer5 == answer5)
{
    correct5 =1;
}
else 
{
 correct5 = 0;   
}

testScore = correct1 +correct2 + correct3 + correct4 + correct5;
System.out.println ("You received a score of " +  testScore + "/5!");

}
}
    
