import static java.awt.SystemColor.text;
import java.util.List;
import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.control.Label;
import javafx.scene.control.TextField;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;
import java.util.Stack;
import javafx.beans.property.SimpleStringProperty;
import javafx.beans.property.StringProperty;
import javafx.event.ActionEvent;
import javafx.event.EventHandler;
import javafx.scene.control.Alert;
import javafx.scene.control.Alert.AlertType;
import javafx.scene.control.TextFormatter;
import javafx.scene.layout.GridPane;
import javafx.scene.text.Text;
import javafx.util.converter.NumberStringConverter;


public class OutputExampleFX extends Application {
    Stack<Integer> opnds = new Stack<>();
    Stack<Character> optr = new Stack<>();
    private TextField expField = new TextField();
    private Label resultLabel = new Label();
    private Label resultTypeLabel = new Label();
    @Override
    public void start(Stage primaryStage) {
        VBox root = new VBox(20);
        root.getChildren().add(expField);
        TextField tx1=new TextField();
        TextField tx2=new TextField();
        TextField t1=new TextField();
        TextField t11=new TextField();
        TextField t2=new TextField();
        TextField t21=new TextField();
        TextField t3=new TextField();
        TextField t31=new TextField();
        TextField t4=new TextField();
        TextField t41=new TextField();
        TextField t5=new TextField();
        TextField t51=new TextField();
        TextField t6=new TextField();
        TextField t61=new TextField();
        Alert a = new Alert(AlertType.NONE);
       
         Label n1=new Label("Name");
         Label n2=new Label("Question Number");
         Label n3=new Label("1");
         Label n4=new Label("2");
         Label n5=new Label("3");
         Label n6=new Label("4");
         Label n7=new Label("5");
         Label n8=new Label("6");
         Text tt= new Text();
         Button btn=new Button("See Result");
        Label code=new Label("Code");
        Label l1=new Label("x=3+4");
        Label l2=new Label("x=3.0+4");
        Label l3=new Label("x=1/2");
        Label l4=new Label("x=1*2");
        Label l5= new Label("String clouds = 'thunder';"
               + "String sun = 'bright';"
               + "x=clouds.length()+sun.length():");
       Label l6 =new Label("String clouds='thunder';"
               + "x=clouds.toUpperCase();");
       Label Student_id=new Label("Studentid");
       Label type = new Label("Type");
       Label value =new Label("Value");
       
       btn.setOnAction(new EventHandler<ActionEvent>(){
       @Override
       public void handle(ActionEvent event){
       TextField[] textFields = {t1, t2, t3, t4, t5, t6,t11,t21,t31,t41,t51,t61};  
       for (TextField textField : textFields) {
               String className = textField.getText();
     
     
     
     
    if (className.equals("Integer")|| className.equals("String")||
            className.equals("Double") || className.equals("7") ||
            className.equals("3.4") || className.equals("0.5") ||
            className.equals("2") || className.equals("13") || className.equals("THUNDER")) {
     
                // set alert type
                a.setAlertType(AlertType.CONFIRMATION);
 
                // show the dialog
                a.show();
            }
       
               

    else
    {
       
                // set alert type
                a.setAlertType(AlertType.ERROR);
 
                // show the dialog
                a.show();
            }
       }
    }

            private boolean validateTextFields(TextField[] textFields) {
                throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
            }
        });
       
 
       
       GridPane grid=new GridPane();
       Scene scene=new Scene(grid,800,800);
        grid.add(n1,0,0);
        grid.add(tx1,1,0);
        grid.add(Student_id,2,0);
        grid.add(tx2,3,0);
        grid.add(n2,0,1);
        grid.add(code,1,1);
        grid.add(type,2,1);
        grid.add(value,3,1);
        grid.add(n3,0,2);
        grid.add(l1,1,2);
        grid.add(t1,2,2);
        grid.add(t11,3,2);
        grid.add(n4,0,3);
        grid.add(l2,1,3);
        grid.add(t2,2,3);
        grid.add(t21,3,3);
        grid.add(n5,0,4);
        grid.add(l3,1,4);
        grid.add(t3,2,4);
        grid.add(t31,3,4);
        grid.add(n6,0,5);
        grid.add(l4,1,5);
        grid.add(t4,2,5);
        grid.add(t41,3,5);
        grid.add(n7,0,6);
        grid.add(l5,1,6);
        grid.add(t5,2,6);
        grid.add(t51,3,6);
        grid.add(n8,0,7);
        grid.add(l6,1,7);
        grid.add(t6,2,7);
        grid.add(t61,3,7);
        grid.add(btn,8,4);
        grid.add(tt,9,4);
       
       
               
        primaryStage.setTitle("Types and Expressions");
       primaryStage.setScene(scene);
       primaryStage.show();
    }
    public static void main(String[] args) {
        launch(args);
    }
}
