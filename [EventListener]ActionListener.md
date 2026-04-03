

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

