<h1>FAQ ?</h1>
<br>
<h3>How to edit config.py</h3>

<p> Here is sample edited config.py for deploy to Locally/VPS. copy and past and edit with your variables</p>

<pre>
class Config(object):

    # get a token from @BotFather
    BOT_TOKEN = "5568340867:AAGuPzlgwqgHtgqmdL7yt12PRLrXFjt98Zg"
    
    # Get these values from my.telegram.org
    API_ID = 12345
    API_HASH = "uPzlgwqgHtgqmdL7yt12PRLrXFj"
    
    # No need to change
    DOWNLOAD_LOCATION = "./DOWNLOADS"
    ADMIN_LOCATION = "./ADOWNLOADS"
    CREDENTIALS_LOCATION = "./CREDENTIALS"
    ADL_BOT_RQ = {}
    CHUNK_SIZE = 128
    TG_MAX_FILE_SIZE = 4194304000
    HTTP_PROXY = ""
    PROCESS_MAX_TIMEOUT = 3700
    DEF_WATER_MARK_FILE = ""
    
    # TG Ids
    LOG_CHANNEL = -1001798969594
    OWNER_ID = 1288398723
    
    # bot username without @
    BOT_USERNAME = "AdvanceUrlUploaderBot"
    
    # auth users
    AUTH_USERS = [1288398722, 1288398724, 1288398725]
    AUTH_USERS.append(OWNER_ID)
</pre>
