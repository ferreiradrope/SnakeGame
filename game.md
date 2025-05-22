import javax.swing.JFrame;

public class JanelaPrincipal extends JFrame {

   public JanelaPrincipal() {
      super("Jogo da Cobrinha");
      setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
      setSize(600, 400);
      setResizable(false);
      setLocationRelativeTo(null);
      setVisible(true);
   }

   public static void main(String[] args) {
      new JanelaPrincipal();
   }
}

