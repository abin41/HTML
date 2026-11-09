# COLLAGE
COLLEGE OF ENGINEERING VADAKARA
-----------------------------------
<img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/1d52392a-3c96-4989-8010-37b884bb7a67" />

# HTML-PROGRAMS

Web Programming Lab record — **20MCA133**, 1st Semester MCA (2024–26), College of Engineering Vadakara.
Reconstructed from the lab record PDF (`WEB_record_1_7y1b.pdf`, submitted by Rahbar Zahid S, Reg. No. VDA24MCA-2039, January 2025).

15 experiments, one folder each. Every folder has its source file(s), a short README, and a rendered screenshot (`output.png`).

## Index

| Exp No | Title | Date | Folder | Files |
|---|---|---|---|---|
| 1 | Basic Tags | 25-09-2024 | PROGRAM1 | Basic.html |
| 2 | Image, Table and Link | 09-10-2024 | PROGRAM2 | Link.html, Image.html, Table.html |
| 3 | Frames | 09-10-2024 | PROGRAM3 | frame.html, pages.html, floating.html, welcome.html, start.html |
| 4 | Registration form using HTML | 06-11-2024 | PROGRAM4 | Form.html |
| 5 | CSS — External, Internal & Inline | 06-11-2024 | PROGRAM5 | Inline.html, Internal.html, External.html, style.css |
| 6 | Predefined functions in JS — String and Math | 13-11-2024 | PROGRAM6 | string-math.html |
| 7 | Calendar using JS | 20-11-2024 | PROGRAM7 | calendar.html |
| 8 | Registration form using JS validation | 27-11-2024 | PROGRAM8 | form-validation.html |
| 9 | Event handling — background colour change | 11-12-2024 | PROGRAM9 | change-color.html |
| 10 | Mouse event handling | 11-12-2024 | PROGRAM10 | mouse-event.html |
| 11 | Online quiz | 18-12-2024 | PROGRAM11 | quiz.html |
| 12 | Registration form using PHP | 19-12-2024 | PROGRAM12 | registration.php |
| 13 | Electricity Bill using PHP | 20-12-2024 | PROGRAM13 | electricity-bill.php |
| 14 | Sort names using asort & arsort | 21-12-2024 | PROGRAM14 | sort-names.php |
| 15 | Cricket players table using PHP | 23-12-2024 | PROGRAM15 | cricket-players.php |

**Note — Exp. 7 / 8 swap:** the record's index lists the JS-validation form as No. 7 and the calendar as No. 8, but the body pages date the calendar 20-11-2024 and the validation form 27-11-2024. The folders follow the body dates (calendar = PROGRAM7, validation = PROGRAM8); each folder README notes this.

## How to use

- **HTML / JS programs (1–11):** open the main file in any browser.
- **PHP programs (12–15):** needs PHP — run `php -S localhost:8000` inside the program folder, then open `http://localhost:8000/<file>.php`. Each PHP folder also has an `output.html` with the expected rendered output for a sample input.
- **Screenshots:** every folder has `output.png` (rendered in headless Chrome at 1280x900). Programs 2, 3 and 5 have extra screenshots for their sub-files; programs 7, 9 and 11 also have an `output-initial.png` (before interaction) alongside the after-interaction `output.png`.

## Notes

- Sources were reconstructed faithfully from the record. Only broken syntax that stops a page rendering was fixed — see each folder README for the exact fixes (e.g. Program 2's broken link, Program 4's invalid colour, Program 8's swapped mobile/username variables, Program 10's mismatched element id).
- Images named in the record (`cev.jpg`, `mca.jpg`, `mca1.jpg`, `thankyou.jpg`) were not in the PDF, so locally generated placeholder images are used instead. Programs 2 and 10 link to the original external image URLs as printed.
- `php` was not installed on the machine that built this, so the PHP `output.html` files are the expected output evaluated by hand from the code (sample inputs are noted in each folder README).
