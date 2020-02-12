public class Game extends Canvas implements Runnable {

public Game() {
  this.setPreferredSize(new Dimension(480,480));
}

public void tick() {


}

public void render(Graphics g){
    BufferStrategy bs = this.getBufferStrategy();
    if(bs == null){
        this.getBufferStrategy(3);
        return;
    }
    Graphics g = bs.getDrawGraphics():
    g.setColor(Color, black);
    g.fillRect(0, 0, 480, 480);
    
    g.dispose();
    bs.show();
}

public static void main(String args[]){
        Game game = new Game();
        JFrame frame = new JFrame("Cobrinha");
        frame.add(game);
        frame.setResizable(false);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        
        frame.pack();
        frame. setLocationRelativeTo(null);
        frame.setVisible(true);
        new Thread(game).start();
}


public void run(){
  while(true){
    tick();
    render():
    Thread.sleep(1000/60);
  
  }
}

}
