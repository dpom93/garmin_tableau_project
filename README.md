# Dashboard Overview: My Garmin Activities Insights
[Tableau Dashboard](https://public.tableau.com/app/profile/drew.pomeroy/viz/GarminDashboardProject/Dashboard1)

# Purpose and Objective
Since 2019, I have lost 40 pounds, and during that time, I have religiously worn a Garmin watch. This project aims to analyze the activities and trends that have contributed to my fitness achievements over the years, identifying what has worked best to reach this fitness level.

## Dashboard 1: Yearly and Monthly Activity Overview (2019 - 2024)
This dashboard provides a comprehensive overview of my Garmin-tracked activities from 2019 to 2024. It is divided into two main sections:

**Yearly Activity Summary**

Total Time in Activities: This section visualizes the cumulative time spent on all activities for each year using a stacked bar chart. The bars are segmented by activity type, offering insights into how my focus on different activities has evolved over the years.
Monthly Activity Breakdown

Monthly Distribution: This area breaks down the selected activities on a monthly basis within each year. Users can pivot between different years and activity types using the filter section to gain detailed monthly insights, ideal for understanding seasonal trends and variations in activity levels.

**Navigation and Interactivity**

Navigation Button: Positioned in the upper right-hand corner, this button directs users to the second dashboard, enabling seamless transitions between different levels of data granularity.

## Dashboard 2: Weekly Activity Insights
This dashboard delves into a more granular analysis, focusing on weekly trends within the selected year:

**Weekly Activity Overview**

This section offers a breakdown of activities by week, providing insights into consistency and intensity on a week-to-week basis. The stacked bar charts illustrate how different activity types contribute to the total time spent each week.

**Filtering Options**

Similar to the first dashboard, users can filter by year and activity type, enabling a focused view of specific activities over time.

# Insights from My Garmin Activities Dashboard

## 2022: The Year of Dedication

- **Highest Activity Time in 2022**: The data reveals that 2022 was the peak year for my fitness journey, with the most time spent on activities. This was the year I committed fully to tracking every activity, no matter how small, including short walks and yoga sessions.

- **Significant Increases in Activity Time**:
  - **Yoga**: 2,065 minutes more in 2022 compared to 2023.
  - **Walking**: 3,996 minutes more in 2022 compared to 2023.
  - **Mountain Biking**: 2,443 minutes more in 2022 compared to 2023.

- **Reasons for Increased Activity**:
  - The 75 Hard Challenge I started in 2022 was a major driver. The challenge required two workouts of at least 45 minutes each day and a goal of 10,000 steps, leading to a substantial increase in the number of activities and time spent.
  - A significant mountain biking trip to Moab, UT, Fruita, CO, and Crested Butte, CO, in April 2022 led to a sharp increase in mountain biking. This trip renewed my enthusiasm for mountain biking, resulting in a notable rise in total ascent from 5,472 feet in April to 9,051 feet in May.

- **Performance and Heart Rate Improvements**:
  - The weekly view shows a peak in week 17 (during the mountain biking trip), followed by two weeks of recovery, and then a renewed increase in mountain biking activity.
  - There was also a noticeable decrease in my average heart rate during April to June, indicating improved fitness during this focused period of mountain biking.

## 2023: A Shift in Focus

- **Increase in Cardio**: While overall activity time decreased from 22,167 minutes in 2022 to 18,224 minutes in 2023, there was a notable shift in focus towards cardio sessions. This reflects a transition in my fitness goals, emphasizing strength training while maintaining a reasonable level of mountain biking.

- **Tracking Adjustments**:
  - Unlike in 2022, I didn’t track every single activity. After completing the 75 Hard Challenge, I became more intuitive with my body’s needs and didn’t feel the need to track certain activities, such as walking and yoga, as meticulously.
  - Hiking saw a 1,000-minute increase, aligning with my goal to hike more in 2023.

## 2024: Continuing the Trend

- **Cardio as a Priority**: As of August 2024, cardio sessions have become an integral part of my daily routine, with over 5,100 minutes tracked so far. This puts me on pace to exceed the previous year's time spent on cardio.

- **Mountain Biking and Hiking**:
  - Both activities are on track to match or exceed last year’s time spent.
  - The increased average heart rate during mountain biking (rising from ~125 to ~140) reflects the more challenging terrain in my new location, requiring higher intensity rides.

- **Changes in Walking**:
  - My goal has shifted from tracking walking time to focusing on daily steps (7,000 to 8,000 per day), which has led to a decrease in tracked walking activities.

- **Summer Challenges**:
  - The summer months in Phoenix have posed challenges, leading to a decrease in weekly distance, calories burned, and total ascent due to the extreme heat and reduced riding opportunities.

## Overall Reflections

- **2022**: Marked by dedication and rigorous tracking, 2022 saw the most significant increase in total activity time, with a clear focus on a wide variety of activities. The year’s highlight was the mountain biking trip, which had a lasting impact on my fitness journey.

- **2023**: This year represented a shift in priorities. While total tracked time decreased, the focus on cardio and selective tracking showed a maturation in how I approach my fitness goals, emphasizing quality over quantity.

- **2024**: The current year is continuing the trend from 2023, with a strong focus on cardio and maintaining consistency in mountain biking and hiking. Adjustments in tracking reflect a more personalized approach to my fitness journey.

## Conclusion

Over the years, my approach to fitness has evolved from tracking everything to focusing on what matters most. I’ve identified activities that no longer need to be meticulously tracked, as my goals and metrics have shifted. As a result, I’m now at my strongest and leanest, with a clear understanding of which activities and goals are most beneficial for my body.


### Design Choices
My goal was to create a dashboard that is both simple and user-friendly. The color scheme reflects this simplicity, with minimal colors used to keep the focus clear while boldly highlighting areas for user interactivity, such as navigation and filters. The first dashboard provides an overview of how my activities have evolved throughout my journey, while the second dashboard allows users to drill down into weekly trends for deeper insights.

### Challenges and Solutions
Several fields required transformation to be effectively used in the visualizations. For example, "Total Ascent" and "Total Descent" needed to be converted from strings to numbers. Additionally, "Total Time" required a custom calculation to convert it from a date/time format to a duration format for accurate analysis.

### Potential Use Cases
This dashboard offers valuable insights into general fitness trends, performance over the years, and highlights which activities have been most consistent throughout my weight loss journey. These insights are crucial for maintaining long-term consistency in a fitness routine.

### Future Enhancements
Currently, this data is limited to activities recorded with my Garmin watch. Integrating additional data such as sleep patterns and steps not recorded during activities would provide a more comprehensive view of my overall health and fitness trends.

### Final Thoughts
This dashboard serves as a powerful tool not only for tracking and visualizing my fitness journey but also for identifying the key factors that have driven my success. By focusing on user-friendly design and meaningful insights, this project showcases my ability to transform raw data into actionable intelligence. The challenges I encountered, such as data transformation and visualization, demonstrate my problem-solving skills and technical proficiency in Tableau. As I continue to enhance this dashboard with additional data sources and features, it will evolve into an even more robust tool for monitoring and optimizing health and fitness, providing valuable lessons for anyone on a similar journey. This project highlights my capability to deliver impactful, data-driven solutions that can be applied to various aspects of personal and professional growth.
