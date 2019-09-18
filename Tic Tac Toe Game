package test;
/*
 * @AUTHOR Julian Garcia
 */

import java.util.ArrayList;
import java.util.Scanner;

public class TestClass {

	public static void main(String[] args) {
		boolean endgame = false; // Determines if the game is won/lost
		int i = 0; // determines if there's a draw or not
		String player = "1"; // an instance variable taking account who's player
								// 1 and 2
		XorO obj1 = new XorO("1");
		XorO obj2 = new XorO("2");
		XorO obj3 = new XorO("3");
		XorO obj4 = new XorO("4");
		XorO obj5 = new XorO("5");
		XorO obj6 = new XorO("6");
		XorO obj7 = new XorO("7");
		XorO obj8 = new XorO("8");
		XorO obj9 = new XorO("9");

		while (endgame == false && i < 9) {
			System.out.println("+-+-+-+");
			System.out.println("|" + obj1.getString() + "|" + obj2.getString() + "|" + obj3.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj4.getString() + "|" + obj5.getString() + "|" + obj6.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj7.getString() + "|" + obj8.getString() + "|" + obj9.getString() + "|");
			System.out.println("+-+-+-+" + "\n");

			String temp = "";
			if (player == "1") {
				temp = "X";
			}
			if (player == "2") {
				temp = "O";
			}
			System.out.println("Player " + player + ": Replacing Which Number? (Only 1-9)");
			Scanner s2 = new Scanner(System.in);
			int temp2 = s2.nextInt();

			// Statements that replace the corresponding number with 'X' or 'O'
			if (temp2 == 1 && (obj1.getString() == "1")) {
				if (temp.contains("X")) {
					obj1.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj1.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 2 && (obj2.getString() == "2")) {
				if (temp.contains("X")) {
					obj2.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj2.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 3 && (obj3.getString() == "3")) {
				if (temp.contains("X")) {
					obj3.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj3.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 4 && (obj4.getString() == "4")) {
				if (temp.contains("X")) {
					obj4.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj4.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 5 && (obj5.getString() == "5")) {
				if (temp.contains("X")) {
					obj5.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj5.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 6 && (obj6.getString() == "6")) {
				if (temp.contains("X")) {
					obj6.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj6.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 7 && (obj7.getString() == "7")) {
				if (temp.contains("X")) {
					obj7.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj7.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 8 && (obj8.getString() == "8")) {
				if (temp.contains("X")) {
					obj8.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj8.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			if (temp2 == 9 && (obj9.getString() == "9")) {
				if (temp.contains("X")) {
					obj9.changeString(temp);
					i++;
					player = changePlayer(player);
				} else {
					if (temp.contains("O")) {
						obj9.changeString(temp);
						i++;
						player = changePlayer(player);
					}
				}
			}
			// 8 statements that win the game, very simple thinking
			// max way to win is in 5 steps 
			if (i > 4) {
				ArrayList<String> a = new ArrayList<>();
				// row 1
				a.add(obj1.getString() + obj2.getString() + obj3.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// row 2
				a.add(obj4.getString() + obj5.getString() + obj6.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// row 3
				a.add(obj7.getString() + obj8.getString() + obj9.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// col 1
				a.add(obj1.getString() + obj4.getString() + obj7.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// col 2
				a.add(obj2.getString() + obj5.getString() + obj8.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// col 3
				a.add(obj3.getString() + obj6.getString() + obj9.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				// Diagonal 1
				a.clear();
				a.add(obj1.getString() + obj5.getString() + obj9.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
				// Diagonal 2
				a.add(obj3.getString() + obj5.getString() + obj7.getString());
				if (a.contains("XXX") || a.contains("OOO")) {
					endgame = true;
					break;
				}
				a.clear();
			}
		}
		// ENDING
		if (i == 9 && endgame == false) {
			// Just Draws the board one final time
			System.out.println("+-+-+-+");
			System.out.println("|" + obj1.getString() + "|" + obj2.getString() + "|" + obj3.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj4.getString() + "|" + obj5.getString() + "|" + obj6.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj7.getString() + "|" + obj8.getString() + "|" + obj9.getString() + "|");
			System.out.println("+-+-+-+" + "\n");
			System.out.println("Draw"); //DRAW
		}
		player = changePlayer(player); // Makes sure the player that had the
										// last
										// turn wins
		if (endgame == true) {
			// Just Draws the board one final time
			System.out.println("+-+-+-+");
			System.out.println("|" + obj1.getString() + "|" + obj2.getString() + "|" + obj3.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj4.getString() + "|" + obj5.getString() + "|" + obj6.getString() + "|");
			System.out.println("+-+-+-+");
			System.out.println("|" + obj7.getString() + "|" + obj8.getString() + "|" + obj9.getString() + "|");
			System.out.println("+-+-+-+" + "\n");

			System.out.println("Player " + player + " Wins!");
		}
	}

	// Helper method that switches players
	public static String changePlayer(String player) {
		// Switches between the players
		if (player == "1") {
			player = "2";
		} else {
			player = "1";
		}
		return player;
	}
}
