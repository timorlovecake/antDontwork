import java.awt.Canvas;
import java.awt.Dimension;
import java.awt.Graphics;
import javax.swing.JFrame;
import javax.swing.JPanel;


public class ant extends JPanel{
	JFrame f=new JFrame("window");
	Screen s=new Screen();
	//open window and stuff
	private ant(){
	
	f.setResizable(false);
	f.setVisible(true);
	f.setPreferredSize(new Dimension(600,600));
	f.pack();
	f.repaint();
	
	
	}
	
	public static void main(String[] args) {
	
		ant run=new ant();
	
	
	}
	public void paint(Graphics g){
	g.drawRect(0,0,10,10);
	}
	
	
}
