# showmsg.jv
input msg on(GUI) what is ur name and display it.(GUI)


import javax.swing.JOptionPane;
public class java{
    public static void main (String args[]){
    String result;
    result = JOptionPane.showInputDialog(null, "What is your name?");
    JOptionPane.showMessageDialog(null,"Hello, Good Evening. "+ result + "!");

    }
}
