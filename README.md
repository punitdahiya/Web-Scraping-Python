This project retrieve IDV(maximum claim your insurer will pay if your vehicle is damaged beyond repair or is stolen) value for all make,model and variants of 2 wheelers for march 2021 for all states from website : https://idv.gicouncil.in/

Python selenium is used and to find each element by ID find_element_by_id() is used . To get value of each find_elements_by_tag_name("option").get_attribute("Value") is used. Sometimes network gets slow, to overcome this problem, a while loop is called and whenever the value gets updated, the loop ends.

By optimizing this code, web scraping takes no more than 30 minutes to gather 18,130 rows of data from website. 

This data is stored in csv format.
