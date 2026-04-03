

```
public interface ActionListener extends EventListener {

    /**
     * Invoked when an action occurs.
     * @param e the event to be processed
     */
    public void actionPerformed(ActionEvent e);

}
```

E.g:

```
submiButton.addActionListener(new ActionListener() {
        @Override
        public void actionPerformed(ActionEvent e) {
            String name = nameField.getText();
            JOptionPane.showMessageDialog(frame, "Hello, " + name + "!");
        }
    });

```

_A button is attached to a button press event through “addActionListener” method. This method accepts “ActionListener” object as an argument, which is an interface with an abstract method “actionPerformed(ActionEvent e)”. So we are using “Anonymous Object” and “Anonymous Class” concepts to provide implementation of “actionPerformed” method._</br>

