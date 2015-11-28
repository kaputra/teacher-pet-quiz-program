// ***************************************************************
// StringManips.j ava
//
// Test several methods for manipulating String objects
// ***************************************************************

import java.util.Scanner;


public class MainQuiz
{
	public static void main (String[] args)
	{
		//constants
		final int QUIT = 0;

		int Input;

		//scanner
		Scanner scan = new Scanner(System.in);

		//loop for the whole program
		while(Input != QUIT)
		{
			//call student method

			//calldisplay menu method

			Input = scan.nextInt();

		}

		///print
		System.out.println();


	}//end main method

	public void display_menu()
	{
		System.out.println();
		System.out.println();
		System.out.println();
		System.out.println();
		System.out.println();

	}// end menu method

	public void student_menu(int input)
	{
		//get name
		student_name = scan.nextLline();

		//get class
		student_class = scan.nextLine();

		//get date
		date = scan.nextInt();


		//3 difficulties easy, medium, hard
		if(difficulty = EASY)
		{
		 	//call questions method

		}
		else if(difficulty = MEDIUM)
		{
			//call questions method
		}
		else
		{
			//call questions method
		}

	}//end student menu method

	public void questions_easy(int difficulty)
	{
		//list of questions here


	}//end question method

	public void questions_medium(int difficulty)
	{
		//list of questions here


	}//end question method

	public void questions_hard(int difficulty)
	{
		//list of questions here


	}//end question method

}end class
