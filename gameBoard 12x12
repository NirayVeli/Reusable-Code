// Java Swing practise 12x12

import javax.swing.*;
import java.awt.*;

public class GameBoard extends JPanel {

    // Filling the gameBoard
    public void paint(Graphics g){
        g.fillRect(100,100,600,600);
        for(int i = 100; i <= 600; i += 100){
            for(int j = 100; j <= 600; j += 100){
                g.clearRect(i,j,50,50);
            }
        }

        for(int i = 150; i <= 650; i += 100){
            for(int j = 150; j <= 650; j += 100){
                g.clearRect(i,j,50,50);
            }
        }
    }

    // Creating gameBoard
    public static void main(String[] args) {
        JFrame frame = new JFrame();
        frame.setSize(900, 800);
        frame.getContentPane().add(new GameBoard());
        frame.setLocationRelativeTo(null);
        frame.setBackground(Color.LIGHT_GRAY);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setVisible(true);
    }

}
