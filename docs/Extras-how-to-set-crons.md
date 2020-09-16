# How to set crons

Cron is a program that enables users to execute commands automatically at a specific time. On Yclas ii is usually used for generating the website's sitemap.

## How to set up your cron

Crons are enabled by default but you can disable it if you want.

![disablecrontab](https://raw.githubusercontent.com/yclas/guides/master/images/disablecrontab.png)

## How to edit or add New Crontab

This part is only for advanced users.

**Steps:**

Login to your **Admin Panel** ->  **Tools**  ->  **Crontab**  and click the  **Edit**  button next to the crotab you want to update.

![crontabedit](https://raw.githubusercontent.com/yclas/guides/master/images/crontabedit.png)

If you want to  **add a New Crontab** clik on **New**.

![crontabnew](https://raw.githubusercontent.com/yclas/guides/master/images/crontabnew.png)


## How to filter Crontabs

 Go to **Tools**  ->  **Crontab** -> **Filter**
 You can use the filter to search for specific Crontabs. You can filter Crontabs on the basis of **running** and **active**.
 
![crontabfilter](https://raw.githubusercontent.com/yclas/guides/master/images/crontabfilter.png)


The function needs to be a static method.

-   **Name:**  The name of the crontab.
-   **Period:**  When this command will be executed.
-   **Callback:**  The command you want to execute.
-   **Params:**  The parameters the function receives.
-   **Description:**  Description of the crontab.
-   **Date Started:**  Date and time the last execution started.
-   **Date Finished:**  Date and time the last execution finished.
-   **Date Next:**  Date and time of the next execution.
-   **Times Executed:**  How many times this crontab executed.
-   **Output:**  The message returns.
-   **Running:**  Checked if crontab is running.
-   **Active:**  Checked if crontab is active.



*This guide is only for Yclas Self-hosted*
