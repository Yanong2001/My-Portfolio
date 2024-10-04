<?php
use PHPMailer\PHPMailer\PHPMailer;
use PHPMailer\PHPMailer\Exception;

require 'phpmailer/src/Exception.php';
require 'phpmailer/src/PHPMailer.php';
require 'phpmailer/src/SMTP.php';

if(isset($_POST["send"])) {
    // Form fields
    $email = $_POST["email"];
    $name = $_POST["name"];
    $contact = $_POST["contact"];
    $message = $_POST["message"];

    // PHPMailer
    $mail = new PHPMailer(true);
    $mail->isSMTP();
    $mail->Host = 'smtp.gmail.com';
    $mail->SMTPAuth = true;
    $mail->Username = 'ponclara2001@gmail.com';
    $mail->Password = 'dbdtjfimkrtqinnp';
    $mail->SMTPSecure = 'ssl';
    $mail->Port = 465;

    // Sender and recipient
    $mail->setFrom('ponclara2001@gmail.com', 'Rialyn');
    $mail->addAddress($email, $name); 

    // Content
    $mail->isHTML(true);
    $mail->Subject = 'Contact Form Submission';
    $mail->Body = "Name: $name <br> Email: $email <br> Contact: $contact <br> Message: $message";

    // Send mail
    if ($mail->send()) {
        echo '<script>alert("Sent Successfully"); document.location.href = "index.php";</script>';
    } else {
        echo 'Message could not be sent.';
        echo 'Mailer Error: ' . $mail->ErrorInfo;
    }
}
?>
