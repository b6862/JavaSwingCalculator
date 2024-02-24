import java.awt.Color;
import java.awt.Font;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.SwingConstants;

public class Calculator implements ActionListener {
	
	JFrame jf;
	JLabel displayLabel;
	
	String expression = "";
	char operator;
			
	JButton sevenButton;
	JButton eightButton;
	JButton nineButton;
	JButton fourButton;
	JButton fiveButton;
	JButton sixButton;
	JButton oneButton;
	JButton twoButton;
	JButton threeButton;
	JButton dotButton;
	JButton zeroButton;
	JButton equaltoButton;
	JButton divButton;
	JButton mulButton;
	JButton minusButton;
	JButton plusButton;
    JButton clearButton;
	
	
	public Calculator() {
		
		jf=new JFrame("Calculator");
		jf.setLayout(null);
		jf.setSize(450, 640);
		jf.setLocation(300, 90);
		
		displayLabel=new JLabel();
		displayLabel.setBounds(30, 40, 380, 60);
		displayLabel.setBackground(Color.WHITE);
		displayLabel.setOpaque(true);
		displayLabel.setHorizontalAlignment(SwingConstants.RIGHT);
		displayLabel.setForeground(Color.black);
		displayLabel.setFont(new Font("arial", Font.BOLD, 44));
		jf.add(displayLabel);
		
		sevenButton=new JButton("7");
		sevenButton.setBounds(30, 120, 80, 80);
		sevenButton.addActionListener(this);
		sevenButton.setFocusPainted(false);
		sevenButton.setFont(new Font("Arial", Font.PLAIN, 35));
		sevenButton.setBackground(Color.white);
	
		jf.add(sevenButton);
		
		
		eightButton=new JButton("8");
		eightButton.setBounds(130, 120, 80, 80);
		eightButton.addActionListener(this);
		eightButton.setFocusPainted(false);
		eightButton.setFont(new Font("Arial", Font.PLAIN, 35));
		eightButton.setBackground(Color.white);
		jf.add(eightButton);
		
		nineButton=new JButton("9");
		nineButton.setBounds(230, 120, 80, 80);
		nineButton.addActionListener(this);
		nineButton.setFocusPainted(false);
		nineButton.setFont(new Font("Arial", Font.PLAIN, 35));
		nineButton.setBackground(Color.white);
		jf.add(nineButton);
		
	    fourButton=new JButton("4");
		fourButton.setBounds(30, 220, 80, 80);
		fourButton.addActionListener(this);
		fourButton.setFocusPainted(false);
		fourButton.setFont(new Font("Arial", Font.PLAIN, 35));
		fourButton.setBackground(Color.white);
		jf.add(fourButton);
		
		fiveButton=new JButton("5");
		fiveButton.setBounds(130, 220, 80, 80);
		fiveButton.addActionListener(this);
		fiveButton.setFocusPainted(false);
		fiveButton.setFont(new Font("Arial", Font.PLAIN, 35));
		fiveButton.setBackground(Color.white);
		jf.add(fiveButton);
		
		sixButton=new JButton("6");
		sixButton.setBounds(230, 220, 80, 80);
		sixButton.addActionListener(this);
		sixButton.setFocusPainted(false);
		sixButton.setFont(new Font("Arial", Font.PLAIN, 35));
		sixButton.setBackground(Color.white);
		jf.add(sixButton);
		
		oneButton=new JButton("1");
		oneButton.setBounds(30, 320, 80, 80);
		oneButton.addActionListener(this);
		oneButton.setFocusPainted(false);
		oneButton.setFont(new Font("Arial", Font.PLAIN, 35));
		oneButton.setBackground(Color.white);
		jf.add(oneButton);
		
		twoButton=new JButton("2");
		twoButton.setBounds(130, 320, 80, 80);
		twoButton.addActionListener(this);
		twoButton.setFocusPainted(false);
		twoButton.setFont(new Font("Arial", Font.PLAIN, 35));
		twoButton.setBackground(Color.white);
		jf.add(twoButton);
		
		threeButton=new JButton("3");
		threeButton.setBounds(230, 320, 80, 80);
		threeButton.addActionListener(this);
		threeButton.setFocusPainted(false);
		threeButton.setFont(new Font("Arial", Font.PLAIN, 35));
		threeButton.setBackground(Color.white);
		jf.add(threeButton);
		
		dotButton=new JButton(".");
		dotButton.setBounds(30, 420, 80, 80);
		dotButton.addActionListener(this);
		dotButton.setFocusPainted(false);
		dotButton.setFont(new Font("Arial", Font.PLAIN, 35));
		dotButton.setBackground(Color.white);
		jf.add(dotButton);
		
		zeroButton=new JButton("0");
		zeroButton.setBounds(130, 420, 80, 80);
		zeroButton.addActionListener(this);
		zeroButton.setFocusPainted(false);
		zeroButton.setFont(new Font("Arial", Font.PLAIN, 35));
		zeroButton.setBackground(Color.white);
		jf.add(zeroButton);
		
		equaltoButton=new JButton("=");
		equaltoButton.setBounds(230, 420, 80, 80);
		equaltoButton.addActionListener(this);
		equaltoButton.setFocusPainted(false);
		equaltoButton.setFont(new Font("Arial", Font.PLAIN, 35));
		equaltoButton.setForeground(Color.green);
		equaltoButton.setBackground(Color.WHITE);
		jf.add(equaltoButton);
		
		divButton=new JButton("/");
		divButton.setBounds(330, 120, 80, 80);
		divButton.addActionListener(this);
		divButton.setFocusPainted(false);
		divButton.setFont(new Font("Arial", Font.PLAIN, 35));
		divButton.setBackground(Color.black);
		divButton.setForeground(Color.white);
		jf.add(divButton);
		
		mulButton=new JButton("x");
		mulButton.setBounds(330, 220, 80, 80);
		mulButton.addActionListener(this);
		mulButton.setFocusPainted(false);
		mulButton.setFont(new Font("Arial", Font.PLAIN, 35));
		mulButton.setBackground(Color.black);
		mulButton.setForeground(Color.white);
		jf.add(mulButton);
		
		minusButton=new JButton("-");
		minusButton.setBounds(330, 320, 80, 80);
		minusButton.addActionListener(this);
		minusButton.setFocusPainted(false);
		minusButton.setFont(new Font("Arial", Font.PLAIN, 35));
		minusButton.setBackground(Color.black);
		minusButton.setForeground(Color.white);
		jf.add(minusButton);
		
		plusButton=new JButton("+");
		plusButton.setBounds(330, 420, 80, 80);
		plusButton.addActionListener(this);
		plusButton.setFocusPainted(false);
		plusButton.setFont(new Font("Arial", Font.PLAIN, 35));
		plusButton.setBackground(Color.black);
		plusButton.setForeground(Color.white);
		jf.add(plusButton);
		
		clearButton=new JButton("C");
		clearButton.setBounds(330, 517, 80, 80);
		clearButton.addActionListener(this);
		clearButton.setFocusPainted(false);
		clearButton.setFont(new Font("Arial", Font.PLAIN, 39));
		clearButton.setForeground(Color.red);
		clearButton.setBackground(Color.WHITE);
		jf.add(clearButton);
		
				
		jf.setVisible(true);
		jf.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		
	}
	
	public static void main(String[] args) {
		new Calculator();
		
		
	}
	
	@Override
	public void actionPerformed(ActionEvent e) {
		if (e.getSource() == sevenButton) {
			expression += String.valueOf(7);
            displayLabel.setText(displayLabel.getText() + "7");
		} else if (e.getSource() == eightButton) {
			expression += String.valueOf(8);
            displayLabel.setText(displayLabel.getText() + "8");
        } else if (e.getSource() == nineButton) {
			expression += String.valueOf(9);
            displayLabel.setText(displayLabel.getText() + "9");
        } else if (e.getSource() == fourButton) {
			expression += String.valueOf(4);
            displayLabel.setText(displayLabel.getText() + "4");
        } else if (e.getSource() == fiveButton) {
			expression += String.valueOf(5);
            displayLabel.setText(displayLabel.getText() + "5");
        } else if (e.getSource() == sixButton) {
			expression += String.valueOf(6);
            displayLabel.setText(displayLabel.getText() + "6");
        } else if (e.getSource() == oneButton) {
			expression += String.valueOf(1);
            displayLabel.setText(displayLabel.getText() + "1");
        } else if (e.getSource() == twoButton) {
			expression += String.valueOf(2);
            displayLabel.setText(displayLabel.getText() + "2");
        } else if (e.getSource() == threeButton) {
			expression += String.valueOf(3);
            displayLabel.setText(displayLabel.getText() + "3");
        } else if (e.getSource() == dotButton) {
			expression += String.valueOf(".");
            displayLabel.setText(displayLabel.getText() + ".");
        } else if (e.getSource() == zeroButton) {
			expression += String.valueOf(0);
            displayLabel.setText(displayLabel.getText() + "0");
        } else if (e.getSource() == clearButton) {
			expression = "";
            displayLabel.setText("");
        }
		if (e.getSource() == plusButton) {
			operator = '+';
			expression += "+";
            displayLabel.setText("");
		}
		if (e.getSource() == minusButton) {
			operator = '-';
			expression += "-";
            displayLabel.setText("");
		}
		if (e.getSource() == divButton) {
			operator = '/';
			expression += "/";
            displayLabel.setText("");
		}
		if (e.getSource() == mulButton) {
			operator = '*';
			expression += "*";
            displayLabel.setText("");
		}
		if (e.getSource() == equaltoButton) {
            evaluateExpression();
		}
            
		
		

	}
		private void evaluateExpression() {
	        try {
	            String[] parts = expression.split("(?<=[-+*/])|(?=[-+*/])");
	            double result = Double.parseDouble(parts[0]);

	            for (int i = 1; i < parts.length; i += 2) {
	                String operator = parts[i];
	                double operand = Double.parseDouble(parts[i + 1]);

	                switch (operator) {
	                    case "+":
	                        result += operand;
	                        break;
	                    case "-":
	                        result -= operand;
	                        break;
	                    case "*":
	                        result *= operand;
	                        break;
	                    case "/":
	                        result /= operand;
	                        break;
	                }
	            }

	            displayLabel.setText(String.valueOf(result));
	            expression = String.valueOf(result);
	        } catch (Exception ex) {
	            displayLabel.setText("Error");
	            expression = "";
	        }
		}


}
