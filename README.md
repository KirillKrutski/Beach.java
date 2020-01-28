package objectPractice.HW;
import javax.swing.text.DefaultEditorKit;
public class Beach {
    public static void main(String[] args) {
        women women1 = new women ("Katy",
                    19.0,"+1929481");
        women women2 = new women ("Anna",
                    20.0,"+192930");
        women women3 = new women ("Nasty",
                    22.0,"+192321");
        women women4 = new women ("Anna",
                    21.0,"+1929321");
        System.out.println(women1);
        System.out.println(women2);
        System.out.println(women3);
        System.out.println(women4);
        System.out.println("Code:");
        System.out.println(women1.hashCode());
        System.out.println(women2.hashCode());
        System.out.println(women3.hashCode());
        System.out.println(women4.hashCode());
        System.out.println("women1.equals(women2) = " + women1.equals(women2));
    }
}

