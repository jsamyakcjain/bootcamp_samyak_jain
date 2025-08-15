

# Bootcamp Repository
## Folder Structure
- **homework/** → All homework contributions will be submitted here.
- **project/** → All project contributions will be submitted here.
- **class_materials/** → Local storage for class materials. Never pushed to
GitHub.

## Homework Folder Rules
- Each homework will be in its own subfolder (`homework0`, `homework1`, etc.)
- Include all required files for grading.
## Project Folder Rules
- Keep project files organized and clearly named.
cat > README.md
nano README.md
echo '# Bootcamp Repository' > README.md
echo '## Folder Structure' >> README.md
echo '- **homework/** → All homework contributions will be submitted here.' >> README.md
echo '- **project/** → All project contributions will be submitted here.' >> README.md
echo '- **class_materials/** → Local storage for class materials. Never pushed to GitHub.' >> README.md
echo '' >> README.md
echo '## Homework Folder Rules' >> README.md
echo '- Each homework will be in its own subfolder (`homework0`, `homework1`, etc.)' >> README.md
echo '- Include all required files for grading.' >> README.md
echo '## Project Folder Rules' >> README.md
echo '- Keep project files organized and clearly named.' >> README.md


cat > README.md << EOF
# Bootcamp Repository
## Folder Structure
- **homework/** → All homework contributions will be submitted here.
- **project/** → All project contributions will be submitted here.
- **class_materials/** → Local storage for class materials. Never pushed to GitHub.

## Homework Folder Rules
- Each homework will be in its own subfolder (`homework0`, `homework1`, etc.)
- Include all required files for grading.
## Project Folder Rules
- Keep project files organized and clearly named.
EOF
git add README.md
