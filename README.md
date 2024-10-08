# Toast Notification

This project implements a responsive toast notification system using HTML, CSS, and JavaScript. It provides users with visual feedback in the form of sliding toast messages, each indicating success, error, or invalid input.

<h2>Key Features</h2>
<h3>Toast Notification System</h3>
<h4>Triggering Toasts</h4> 
  Users can trigger different toast messages by clicking buttons labeled "Success," "Error," and "Invalid." Each button is linked to a specific type of notification.

<h4>Dynamic Toast Creation</h4> 
  Toast notifications are dynamically generated using JavaScript. When triggered, the notifications slide in from the right side of the screen, offering a smooth, animated user experience.

<h3>Toast Message Types</h3>
<h4>Success Notification</h4> 
  Displays a green checkmark icon alongside a success message.
<h4>Error Notification</h4> 
  Displays a red cross icon with an error message.
<h4>Invalid Notification</h4> 
  Displays an orange exclamation mark icon with an invalid input message.
<h3>Auto-Dismiss Feature</h3>
<h4>Automatic Removal</h4> 
  Each toast notification automatically disappears after 6 seconds, ensuring the messages do not obstruct the user experience for too long.
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
The HTML file includes a main container where toast notifications are dynamically added. It also features buttons for triggering each type of toast notification.
<h3>CSS Styling</h3>
<h4>Design and Animation</h4> 
The CSS provides a modern look with a sliding animation. Toasts are consistently styled, with appropriate colors and box-shadow effects to distinguish between message types.

<h4>Responsive Layout</h4> 
The toast container is positioned at the bottom-right corner of the screen, making notifications noticeable but unobtrusive.

<h3>JavaScript Functionality</h3>
<h4>Toast Creation Function</h4>
  The <code>showToast</code> function dynamically creates and displays a toast message, applying the appropriate style based on the message type.

    function showToast(msg) {
      //Function implementation
    }

<h4>Animation and Dismissal</h4> 
  The toast notification slides into view with a CSS animation, and an auto-dismiss timer removes the notification after 6 seconds using <code>setTimeout</code>.

    setTimeout(() => {
        toast.remove();
    }, 6000);

<h2>In Summary</h2>
This toast notification project provides a practical and elegant solution for displaying real-time feedback messages. The system's simplicity, combined with smooth animations and responsive design, enhances the user experience without being intrusive.
