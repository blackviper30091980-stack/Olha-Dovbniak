This checklist contains common test scenarios for web application testing.It covers functional, usability,compatibility,performance,database and UI testing and cad be used as a reference during manual testing


# WEB TESTING CHECKLIST

## FUNCTIONAL TESTING
* Check that all links in the header and footer redirect to the correct pages
* Check that there are no broken links
* Check that all buttons are clickable

## USABILITY TESTING
* Check that the navigation menu is intuitive and organized into logical categories
* Check that the page can be zoomed in and out without affecting usability
* Check that registration forms  clearly indicate required fields and request only the minimum necessary information
* Check that tooltips appear when users interact with the corresponding UI elements

## COMPATIBILITY TESTING 
* Check that pages are rendered correctly in different browsers(e.g., Chrome, Firefox, Safary, Edge)
* Check that all UI elements are displayed correctly in the latest browser versions
* Check that pages are displayed correctly on different screen resolutions
* Check that the website performs consistently on devises with different CPU and RAM configurations
* Check that the website functions correctly over Wi-Fi, 4G, 5G and under poor network conditions

## PERFORMANCE TESTING
### Load Testing 
* Check that the website remains stable when 10 000 users place orders simultaneously
### Stress Testing
* Check the website performance on devices with critically low RAM, limited network bandwidth and high CPU usage
### Endurance(Stability) Testing
* Check that the website remains stable when 10 000 users continuously browse the catalog, add items to the cart and place orders for 48-72 hours
### Volume Testing 
* Check that the system remains stable and responsive when more when 1 million records are inserted into the database
### Spike Testing
* Check the website performance when 10 000 users access the website simultaneously during a short period ( e.g., the start of a sale or exam registration)
* Check that the website remains available and identify the expected server response
* Check how quickly the system recovers after the traffic spike
* Check that no data is lost or corrupted during the spike

## DATABASE TESTING
* Check that user data is stored correctly after logging in, logging out and loggin in again
* Check data integrity if power failure occurs during a transaction
* check that users  cannot be deleted if they have active orders

## UI TESTING 
* Check that appropriate  success and error messages are displayed
* Check that pages are displayed consistently across different devices
* Check that website navigation is clear,intuitive and easy to use
* Check that there are no broken images on any page
