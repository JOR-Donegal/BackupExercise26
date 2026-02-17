# Active Directory

Using Server Manager, install Windows Server Backup.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig1.jpg">
<figcaption>Fig 1. Add Roles and Features.</figcaption>
</figure>

Under Server Manager->Tools, run Windows Server Backup.
Select Local Backup and then Backup Once

Under Server Manager->Tools, run Windows Server Backup.
Select Local Backup and then Backup Once.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig2.jpg">
<figcaption>Fig 2. Local backup.</figcaption>
</figure>

Select Different Options and Click Next.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig3.jpg">
<figcaption>Fig 3. Options.</figcaption>
</figure>

Select Backup Configuration, select Custom

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig4.jpg">
<figcaption>Fig 4. Backup Configuration.</figcaption>
</figure>

Under Select Items, Click Add, select System State and click OK.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig5.jpg">
<figcaption>Fig 5. System State.</figcaption>
</figure>

Select Advanced Settings and the select VSS Settings. Enable VSS Full Backup, so that you get a valid backup, even if a change is being made to the directory during the backup.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig6.jpg">
<figcaption>Fig 6. VSS.</figcaption>
</figure>

Click Next.
You should store your backup on a remote shared folder or a dedicated backup disk. In this case, I'm just using C:\. Click Next.

<figure>
<img src = "https://jor-donegal.github.io/BackupExercise26/images/fig7.jpg">
<figcaption>Fig 7. Destination.</figcaption>
</figure>
