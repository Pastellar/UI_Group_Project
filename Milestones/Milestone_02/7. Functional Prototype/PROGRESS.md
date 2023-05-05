# Current Status Of Pages & Related Functionality
### Links
- **Website:**      https://ec2-13-59-221-205.us-east-2.compute.amazonaws.com/Group_temp/index.html

### Planned Pages
> Legend:   [P] Priority    [M] Maybe

- 'Log In / Account Creation'
    - **Log In** [P]
    - **Create Account** [p]
    - **Forgot Password** [p]

- 'Account'
    - **User Account** [p]
        - **Wish List**[M]
        - **Settings** [M]
        - **Orders** [M]
        - **Saved Payment** [M]
    - **Admin Account** [M]
        - **Settings** [M]

- 'Purchasing Product'
    - **Cart** [P]
    - **Checkout** [P]

- 'All'
    - **Home/Main** [P]
    - **Search** [P]
    - **Collection** [P]
        - **Product** [P]


### Current Progress / Status
> As of: 04/18/23
> Legend:   [IP] In Progress    [C] Complete   [] To Do

- 'Log In / Account Creation'
    - **Log In**            [IP]
    - **Create Account**    [IP]
    - **Forgot Password**   []

- 'Account'
    - **User Account**      [IP]
        - **Wish List**     []
        - **Settings**      []
        - **Orders**        []
        - **Saved Payment** []
    - **Admin Account**     []
        - **Settings**      []

- 'Purchasing Product'
    - **Cart**              [IP]
    - **Checkout**          [IP]

- 'All'
    - **Home/Main**         [IP]
    - **Search**            [IP]
    - **Collection**        [IP]
        - **Product**       [IP]


### Functionality
> Not all functionality will be achievable within the scope of this semester, but an attempt will be made

- 'Log In / Account Creation'
    - **Log In**
        - Inner section features a log in form
            - User fills in their username and password in the form boxes
                - error will display if incorrect information is entered
            - forgot password link displayed underneath form
                - clicking link navigates user to forgot password page
            - create account link displayed under form, to the right of forgot password
                - clicking link navigates user to create account page
            - login button displayed underneath form at the bottom
                - clicking button logs user in and navigates them to the home page
                - if incorrect info, error displayed and user not logged in
            - remember me checkbox to the right of login button
                - clicking checkbox will have site remember entered user information for future login attempts

    - **Create Account**
        - Page will display a form (similar to checkout page) for user to fill in and create an account

    - **Forgot Password**
        - Page will feature a simple form for user to enter the email of their account
            - entered email will be sent a link to reset their account password

- 'Account'
    - **User Account**
        - (if logged in) Clicking the My Account link in the top header on the right-most corner will navigate user to their account page
        - (if guest) Clicking the My Account link in the top header on the right-most corner will navigate user to the log in page
        - (if logged in) Clicking the account icon in the inner header section on the right-most side will navigate user to their account page
        - (if guest) Clicking the account icon in the inner header section on the right-most side will navigate user to the log in page
        - Account page will feature the user's details and related information
        - **Wish List**
            - TO DO
        - **Settings**
            - TO DO
        - **Orders**
            - TO DO
        - **Saved Payment**
            - TO DO
    - **Admin Account**
        - TO DO

- 'Purchasing Product'
    - **Cart** 
        - Hovering over Cart icon in header will display a model window of a few items currently in the cart (if any)
            - A bubble with the number of items currently in the cart displays over the icon
            - model window:
                - clicking view cart at top right will navigate user to cart page
                - clicking the x by any item will remove it from the cart
                - current total item cost will display towards the bottom, above the button
                - clicking the checkout button will navigate the user to the checkout page
            - clicking the Cart icon in header will navigate the user to the cart page
            - Cart page displays all items in cart
                - displays item
                - displays price
                - displays quantity
                    - adjustable by clicking the -, +, or typing in the form box
                - total cost
                - trash icon
                    - clicking icon removes item from cart
                - displays coupon form at bottom left
                    - typing in form box allows user to enter coupon code (if applicable)
                    - click apply button (next to form box) to apply the coupon to the cart
                - shipping check box underneath coupon form on bottom left side
                    - click check box to activate shipping as true and apply it to the cart
                - cart cost details displayed in bottom right corner
                    - displays calculated subtotal, shipping, savings, and final payment
                    - displays checkout button
                        - clicking button will navigate user to the checkout page
                    - displays continue shopping
                        - clicking button will navigate user back to the home page

    - **Checkout**
        - Displays a checkout form in the left side of the inner section
            - form boxes for user to enter their
                - name
                - email
                - phone number
                - country
                - state
                - address
                - postal code
            - (if guest) optional checkbox at bottom of form to create an account with the entered information
            - (if logged in) form will be auto-filled with saved account details
        - displays calculated cart total cost and payment options in right side of inner section
            - Cart totals section
                - sub total cost
                - shipping cost
                - total cost
            - payment section
                - check
                - cash
                - paypal
        - displays proceed to checkout button at the bottom
            - clicking button will navigate user to completing the purchase

- 'All'
    - **All Pages**
        - Users can view as guest or log into an account
        
        - Header:
            > Top-most section of site: Spanning from top-most bar to the navigation menu
            - Displays company number and customer support email on top, left-hand side
            - Displays My Account and Login on top, right-hand side
                - (If Logged In) Clicking on My Account will navigate user to their account page
                - (If Guest) Clicking on My Account will navigate user to Login page
                - Clicking on Login will navigate user to Login page
            - Displays Logo

        - Search Bar
            - (optional) Search All
            - (optional) Search Specified Collection
            - Clicking on search bar middle box allows user to input their search query
            - Clicking on the magnifying lens 

        - Navigation Menu:
            - (if applicable) Current menu tab will display as active
            - Home
                - Clicking on tab will navigate user to Home page
            - Collections
                - Dropdown List of available collections
                - Clicking on a collection will navigate user to that collection page
            - Contact Us
                - Clicking on tab will navigate user to Contact page

        - Footer:
            > Bottom-most section of site, defined by its black background
            - Displays Logo in the left-most side
                - Statement & support number listed underneath
            - Information group next to logo (to the right)
                - Help & FAQ link
                    - clicking on link navigates user to the Support/FAQ page
                - Terms & Conditions
                    - clicking on link navigates user to the TOS page
            - Get In Touch Group next to Information Group (right-most group)
                - Lists Company location
                - Lists Company email
                - Lists Company phone number
                - Displays Facebook icon
                    - clicking on icon navigates user to official Shrek Facebook Page
                - Displays Twitter icon
                    - clicking on icon navigates user to twitter page of a bot posting every frame from the Shrek movies
        