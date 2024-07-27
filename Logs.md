## Deolo-dotcom Development Logs

### Version 0.0
- Set up Django environment for project
- Set up Git

### Version 0.1
- Migrations not done (fixed)
- Settings changes for media
- Models for (Category Customer Product Order) at ./store/models.py
- Registration pass on at ./store/admin.py
- Media folder done from Django-admindas

### Version 0.2
- Settings changes for static
- Custom template loaded from Start Bootstrap
- Product showcase in home.html
- Categorys verbose bug (fixed)

### Version 0.3
- Fixes in layout for home.html
- Added base other template layouts in ./store/templates

### Version 0.4
- Added custom CSS structures custom.css
- User authentication Login/Logout
- Register of user using custom forms at ./store/forms.py

### Version 0.5
- Tailwind setup done (Unused)
- User registration changes in ./store/urls.py
- Category and Product view and navigation changed for ./store/urls.py
- Product and Category views at ./store/views.py
- README.md added
- (Caution): Github branch change and random deletions due to false upload of github directory

### Version 0.6
- Store App changed to Shop App (./store is now ./shop)
- Changed setting for Cart App recongize
- Created cart models at ./cart/models/py
- Created contexts for cart logics at ./cart/context_processor.py
- Created URLs for cart at ./cart/urls.py
- Created Cart class with attributes of the Cart App at ./cart/cart.py
- Created the views for Cart at ./cart/views.py
- Cart summary template at ./cart/templates/cart_summary.html
- Created connection to Product and Cart Summary from ./shop/templates/product.html
- Cart icon number change at ./shop/templates/navbar.html
- Temporary .gitattributes added