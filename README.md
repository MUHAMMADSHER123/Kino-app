# Music & Movie Downloader Bot

Bu loyiha Flask yordamida veb-interfeys va Telegram boti orqali YouTube kabi manbalardan musiqa va videolarni qidirish va yuklab olish imkonini beradi.

## O'rnatish va ishga tushirish

1.  **Omborni klonlash:**

    ```bash
    git clone https://github.com/MUHAMMADSHER123/Muhammadsher_2404.git
    cd Muhammadsher_2404
    ```

2.  **Virtual muhit yaratish va faollashtirish (tavsiya etiladi):**

    ```bash
    # Windows
    python -m venv venv
    venv\Scripts\activate

    # macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Kerakli kutubxonalarni o'rnatish:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Telegram Bot Tokenini sozlash:**

    `app.py` fayli Telegram bot tokenini muhit o'zgaruvchisidan (`TELEGRAM_BOT_TOKEN`) o'qishga harakat qiladi. Tokenni o'rnatishning eng oson yo'li - `.env` faylini yaratish va unga tokeningizni yozish.

    -   Loyiha papkasida `.env` nomli fayl yarating.
    -   Fayl ichiga quyidagi qatorni qo'shing va o'z tokeningizni joylang:

        ```
        TELEGRAM_BOT_TOKEN="SIZNING_TELEGRAM_BOT_TOKENINGIZ"
        ```

    *Izoh: `.gitignore` fayli `.env` faylini Git omboriga qo'shishdan saqlaydi, bu sizning tokeningiz xavfsizligini ta'minlaydi.*

5.  **Dasturni ishga tushirish:**

    ```bash
    python app.py
    ```

    Dastur ishga tushgandan so'ng, veb-interfeysga [http://127.0.0.1:8000](http://127.0.0.1:8000) manzili orqali kirishingiz mumkin bo'ladi va Telegram botingiz ham ishlay boshlaydi.
