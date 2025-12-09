<?php
if($_SERVER["REQUEST_METHOD"] == "POST"){
    $name = strip_tags(trim($_POST["name"]));
    $email = filter_var(trim($_POST["email"]), FILTER_SANITIZE_EMAIL);
    $message = trim($_POST["message"]);

    if(empty($name) || empty($message) || !filter_var($email, FILTER_VALIDATE_EMAIL)){
        echo "Please fill all fields correctly.";
        exit;
    }

    $to = "davidyiaro@gmail.com";
    $subject = "New Message from Portfolio Website";
    $body = "Name: $name\nEmail: $email\n\nMessage:\n$message";
    $headers = "From: $email";

    if(mail($to, $subject, $body, $headers)){
        echo "<script>alert('Message sent successfully!'); window.location='index.html';</script>";
    } else {
        echo "<script>alert('Oops! Something went wrong.'); window.location='index.html';</script>";
    }
} else {
    header("Location: index.html");
}
?>
