## 🧭 Contribution guidelines
Welcome Contributors!
Thank you for considering contributing to this project. This document outlines the guidelines for contributing to the development of Shipping Rates and Calculations.

## 🛠 How to Contribute

### **Start with the Issue Tracker**
   - **Check for existing issues**: [Open Issues](https://github.com/jetmirrama/LogisticsShippingRates/issues)  
     Avoid duplicates by searching for your idea/bug first.
   - **Comment to claim an issue**:  
     Write "I’d like to work on this!" to let others know you’re tackling it.
   - **No issue for your idea?**  
     Open a new one! Describe your proposal or bug with details (e.g., steps to reproduce).

### **Set Up Your Local Environment**
   ```bash
   git clone https://github.com/jetmirrama/LogisticsShippingRates.git
   cd LogisticsShippingRates
   pip install -r requirements.txt  # Install dependencies
   ```

### Code Style 
Follow the **existing codebase conventions** (e.g., PEP 8 for Python, camelCase for JS) 
- Use `snake_case` for variables.  
- Avoid trailing whitespace.


## 🚀 Submitting Pull Requests

### **Branch Naming**
- Use descriptive branch names based on the type of change:  
  - `feature/your-feature-name` (e.g., `feature/add-dhl-support`)  
  - `fix/your-bug-fix` (e.g., `fix/rate-calculation-error`)  

### **Describing pull requests**  
- **Title**: Summarize the change (e.g., "Add swiss post rate calculator").  
- **Body**:  
  - Explain **what** you changed and **why**
  - Link related issues with keywords like `Closes #12` or `Fixes #45`.  
  - Add screenshots/GIFs for UI or behavior changes.  

### **Code Review**  
- A maintainer will review your PR
- Be responsive to feedback and update your code if requested.  
- Once approved, your PR will be merged! 🎉  

### **Final Checks**  
- Ensure all tests pass (`pytest tests/`).  
- Update documentation if your change affects any other features.  

## 🎁 First-Time Contributors
New to open-source? Try these [`good first issue`](https://github.com/jetmirrama/LogisticsShippingRates/labels/good%20first%20issue) tasks:
- Improve error messages in the API.
- Add sample data for testing.
- Fix typos in documentation.

## 📝 Documentation  
Update the `README.md` for new features. Use **bold** for key terms:  
> "Shipping rates are calculated based on weight and distance."
