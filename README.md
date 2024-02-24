# Action-Class

1. A utility class facilitating multiple complex user interactions through the use of the Actions class.
   The Actions class serves as a container for a set of individual actions that can be performed on web elements.
3. Actions class is a collection of individual Actions that you want to perform.

 <pre>
import org.openqa.selenium.interactions.Actions;

/**
 * A utility class facilitating multiple complex user interactions through the use of the Actions class.
 * The Actions class serves as a container for a set of individual actions that can be performed on web elements.
 */
public class UserInteractionsHelper {

    public static void main(String[] args) {
        // Create an instance of the Actions class
        Actions actions = new Actions(driver);

        // Use the Actions class to perform various interactions
        // Examples of individual actions include moveToElement, click, dragAndDrop, etc.
        // These actions can be combined to achieve complex user interactions

        // Don't forget to build() and perform() the entire sequence of actions
        // actions.build().perform();
    }
}
   </pre>
