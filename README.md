# CoffeeHut_Backend
# Create and add content to README.md
echo "# Backend Repository

#This repository includes:

- [User Profiles](user_profiles.md)
- [Payment Options](payment_options.md)
- [Commerce Transactions](commerce_transactions.md)
" > README.md

# Create and add content to user_profiles.md
echo "# User Profiles

Documentation for the User Profiles feature.
" > user_profiles.md

# Create and add content to payment_options.md
echo "# Payment Options

Documentation for the Payment Options feature.
" > payment_options.md

# Create and add content to commerce_transactions.md
echo "# Commerce Transactions

Documentation for the Commerce Transactions feature.
" > commerce_transactions.md

# Stage the files for commit
git add README.md user_profiles.md payment_options.md commerce_transactions.md

# Commit the changes
git commit -m "Add documentation files"

# Push to the repository
git push origin main