# Description
## Desktop Computer Components Review System

The web application showcases the best-selling and widely recommended desktop components based on data from commercial shopping websites as well as user-inputted reviews pertaining to each individual component item.

The purpose of the website is to recommend desktop components to the less-informed general public who find themselves uneased by the ostensibly daunting process of building their customized desktops and allow them to take note of reviews written by other users (who went ahead and purchased). This review system differs from those of commercial retail websites in that it isolates itself from any potential sources of bias like the retail companies themselves who may wish to push sales of more profitable items for their own benefit. The user can identify the best-selling desktop components within their specific category of interest (CPU, GPU, keyboards, etc) and make informed purchase decisions without substantial knowledge of computers. On a high level, a user may view the specific best-selling items, submit reviews of items that he or she purchased and has used, as well as read others’ reviews. User may also specify the category, which is reflected on the main page where items within that group is displayed.


## How it meets the feature specification requirements

- User Profiling: if signed up, each user will have own profile picture, selected categories of interest (top selling items among which will be featured on the main webpage view), and their own wish list. All of these can be viewed on their own profile page, along with option to change their data like passwords or categories of interest. Anyone can always check other user’s profile and view their basic information such as interest and wish list. On top of all this, an admin has the authority to delete reviews, choose the items to be displayed, and ban any regular user, as well as access to an exclusive dashboard where they execute said tasks.
- User Authentication and Authorization: login requires username and password matching. Verification feature upon signup may be possible through phone verification as a potential functionality. When they want to post some detail information about some components of computer, there will be a authorization which decide whether user can execute the action or not. There will generally be two types of login: users and admins.
- Data: each computer component will have its own page, containing data of a picture of itself, specifications, user reviews and rating (which can be uploaded by other users or modified by admin) and a demo about that component. The data will be stored in a database and retrieved or uploaded dynamically. Other data pertaining to each individual user’s login credentials as well as user profile settings is managed as well.
- Views: In the main page, if signed up, users have a view of the best-selling products across categories of interest that they have pre-selected. Else, there’s a view of the general best-selling items across all categories. There also exists a view of buttons of all categories on the left where users can enter to view the selection of best-sellers for that group. For each product, there is a product page. Users can view product image, product description, and reviews as well as write their own. (for more details please see Appendix).
- Admin: create pages for popular items not currently in category (as popularity of components in market may change over time); override any form of data regarding a specific component item, including specs, photos, reviews, etc; manually update, add, or delete users’ data; also reset password for users if needed. Also, when user want to request some modifications about detail information about a specific component of computer, admin should decide whether to allow this.


# Author with github ID
 - Yufei Yang: faye-yang
 - Xun Li: lixun94
- Siqi Yang: mephistoshadow
- Jin CHun:developerjinchun

