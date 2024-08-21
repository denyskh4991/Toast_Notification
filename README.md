# Toast Notification

This project implements a responsive toast notification system using HTML, CSS, and JavaScript. It provides users with visual feedback in the form of sliding toast messages, each indicating success, error, or invalid input.

<h2>Key Features</h2>
<h3>Toast Notification System</h3>
<strong>Triggering Toasts</strong> 
  Users can trigger different toast messages by clicking buttons labeled "Success," "Error," and "Invalid." Each button is linked to a specific type of notification.

<strong>Dynamic Toast Creation</strong> 
  Toast notifications are dynamically generated using JavaScript. When triggered, the notifications slide in from the right side of the screen, offering a smooth, animated user experience.

<h3>Toast Message Types</h3>
<strong>Success Notification</strong> 
  Displays a green checkmark icon alongside a success message.
<strong>Error Notification</strong> 
  Displays a red cross icon with an error message.
<strong>Invalid Notification</strong> 
  Displays an orange exclamation mark icon with an invalid input message.
<h3>Auto-Dismiss Feature</h3>
<strong>Automatic Removal</strong> 
  Each toast notification automatically disappears after 6 seconds, ensuring the messages do not obstruct the user experience for too long.
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
The HTML file includes a main container (<code><div id="toastBox"></div></code>) where toast notifications are dynamically added. It also features buttons for triggering each type of toast notification.
<h3>CSS Styling</h3>
<strong>Design and Animation</strong> 
  The CSS provides a modern look with a sliding animation. Toasts are consistently styled, with appropriate colors and box-shadow effects to distinguish between message types.

<strong>Responsive Layout</strong> 
  The toast container is positioned at the bottom-right corner of the screen, making notifications noticeable but unobtrusive.

<h3>JavaScript Functionality</h3>
<strong>Toast Creation Function</strong>
  The <code>showToast</code> function dynamically creates and displays a toast message, applying the appropriate style based on the message type.

    function showToast(msg) {
      //Function implementation
    }

<strong>Animation and Dismissal</strong> 
  The toast notification slides into view with a CSS animation, and an auto-dismiss timer removes the notification after 6 seconds using <code>setTimeout</code>.

    setTimeout(() => {
        toast.remove();
    }, 6000);

<h2>In Summary</h2>
This toast notification project provides a practical and elegant solution for displaying real-time feedback messages. The system's simplicity, combined with smooth animations and responsive design, enhances the user experience without being intrusive.
