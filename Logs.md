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

### Version 0.7
- Update Cart option enabled at ./cart/templates/cart_summary.html
- Bugs at ./cart/urls.py and ./cart/views.py
- Delete Item option enabled at ./cart/templates/cart_summary.html

### Version 0.8
- Total price indicator of Cart products
- Category routing page ./store/category_summary.py
- Messages for cart functions (for adding updating and deleting) at ./cart

### Version 0.9
- User account addition.
- User changes in Name (first and last), Email and Username.
- Password changes authentication activated.
- Template for User Account at ./shop/templates/
- Changes for in ./shop/forms.py

### Version 0.10
- Extended User Profile for address and locations.
- Created new form at ./shop/forms.py.
- Changed navbar style for Profile parts at ./shop/templates/navbar.html.
- New User model created at ./shop/models.py.
- Changes made to admin dashboard via ./shop/admin.py.
- Migrations for the new Profile model.