git clone https://github.com/brigittabc/brigittabc.git](https://github.com/brigittabc/brigittabc.github.io.git
cd brigittabc.github.io

# Create README
cat > README.md << 'EOF'
# Brigitta Busak-Crockett | Senior Project Manager

EOF

# Create a basic HTML page
cat > index.html << 'EOF'
<!DOCTYPE html>
<html>
<head>
    <title>Brigitta Busak-Crockett | Senior Project Manager</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Brigitta</h1>
        <p>Senior Project Manager, Integrated Delivery & Production</p>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I enjoy bringing together creativity, technology and delivery to help teams do their best work.

I have led global campaigns, digital projects, TVC production, social campaigns and AI enabled initiatives across FMCG, beauty, healthcare, technology and telecommunications. My background in design and production gives me a strong understanding of the creative process, while my experience in project and delivery leadership helps keep teams aligned, projects moving and clients confident.

I have delivered work across Europe, North America, Canada, South America and Asia, working with cross-functional teams across multiple markets and time zones. Whether it is a global campaign, a website transformation or an AI initiative, I enjoy bringing structure to complex projects and turning ambitious ideas into successful delivery.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <!-- Add your projects -->
        </section>
    </main>
</body>
</html>
EOF

git add .
git commit -m "Initial portfolio setup"
git push origin main
