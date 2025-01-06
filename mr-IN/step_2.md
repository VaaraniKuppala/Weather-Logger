## तापमान लॉग करने

प्रथम प्रत्येक 5 सेकंदात एखाद्या file वर तपमान लॉग करू. आपण तापमान बदलण्या साठी emulator वापरू शकता.

+ हवामान लॉगर Starter Trinket:<a href="http://jumpto.cc/weather-go" target="_blank">jumpto.cc/weather-go</a> उघडा.
    
    **आपल्यासाठी काही file आणि code जोडले गेले आहेत.**

+ `collect.py` वर क्लिक करा. येथेच आपण तापमान डेटा संकलित करण्यासाठी code लिहा. चला `weather.txt` फाईल उघडू आणि त्या मध्ये दर पाच सेकंदात तापमान लिहू.
    
    हायलाइट केलेला कोड `collect.py` मध्ये जोडा:
    
    ![स्क्रीनशॉट](images/weather-collect.png)
    
    `a` सह फाईल उघडणे म्हणजे फाईलच्या शेवटी डेटा जोडला जाईल.
    
    नवीन ओळ वर्ण लिहिणे `\n` प्रत्येक तापमान वाचनास त्याच्या स्वत: च्या ओळीवर ठेवते.

+ `weather.txt` वर क्लिक करा. ते रिक्त असले पाहिजे. येथेच डेटा संग्रहित केला जाईल.
    
    ![स्क्रीनशॉट](images/weather-file.png)

+ आता Run वर क्लिक करा. तापमान बदलण्या साठी तापमान स्लाइडर मधील emulator वापरा. आपण दर पाच सेकंदात `weather.txt` च्या शेवटी तापमान वाचन जोडलेले पहावे.
    
    लक्षात ठेवा की emulator वास्तविक Sense HAT प्रमाणे वागण्याचा प्रयत्न करतो म्हणून आपण emulator बदलत नसलात तरीही आपल्याला तेच वाचन दिसणार नाही.
    
    ![स्क्रीनशॉट](images/weather-temperature.png)

+ आपण डेटा एकत्र करणे समाप्त केल्यावर `Stop` बटणावर क्लिक करा.
    
    ![स्क्रीनशॉट](images/weather-stop.png)

+ आपण `weather.txt` मधील डेटा हायलाइट करू शकता आणि आपण नवीन तापमान डेटा एकत्र करणे सुरू करू इच्छित असल्यास तो delete करु शकता. सुमारे 10 तपमान रीडिंग एकत्र करा.