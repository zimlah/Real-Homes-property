<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RealHomes and Property - Commercial Real Estate Agency</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }

        /* Color Palette */
        :root {
            --primary-dark-blue: #1e3a8a;
            --primary-blue: #3b82f6;
            --gold-accent: #f59e0b;
            --white: #ffffff;
            --light-gray: #f8fafc;
            --gray-600: #4b5563;
            --gray-800: #1f2937;
        }

        /* Header */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            transition: all 0.3s ease;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--primary-dark-blue), var(--gold-accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--gray-800);
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--primary-dark-blue);
        }

        .mobile-menu {
            display: none;
            flex-direction: column;
            cursor: pointer;
        }

        .mobile-menu span {
            width: 25px;
            height: 3px;
            background: var(--primary-dark-blue);
            margin: 3px 0;
            transition: 0.3s;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(30, 58, 138, 0.7), rgba(30, 58, 138, 0.7)),
                        url('https://images.unsplash.com/photo-1464822759023-fed622b4e435?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
            position: relative;
        }

        .hero-content h1 {
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 700;
            margin-bottom: 1.5rem;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 1s ease forwards;
        }

        .hero-content p {
            font-size: 1.3rem;
            margin-bottom: 2.5rem;
            max-width: 600px;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 1s ease 0.2s forwards;
        }

        .cta-buttons {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 1rem 2.5rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .btn-primary {
            background: var(--gold-accent);
            color: var(--gray-800);
            box-shadow: 0 10px 30px rgba(245, 158, 11, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(245, 158, 11, 0.6);
        }

        .btn-secondary {
            background: transparent;
            color: var(--white);
            border: 2px solid var(--white);
        }

        .btn-secondary:hover {
            background: var(--white);
            color: var(--primary-dark-blue);
        }

        /* Sections */
        section {
            padding: 100px 5%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 4rem;
            color: var(--gray-800);
        }

        /* About Section */
        .about {
            background: var(--light-gray);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .about-text h3 {
            font-size: 1.8rem;
            color: var(--primary-dark-blue);
            margin-bottom: 1.5rem;
        }

        .about-text
