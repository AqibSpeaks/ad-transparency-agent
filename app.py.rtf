{\rtf1\ansi\ansicpg1252\cocoartf2709
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 import streamlit as st\
import requests\
from bs4 import BeautifulSoup\
import pandas as pd\
\
# ---------------------------\
# Streamlit App Starts Here\
# ---------------------------\
st.set_page_config(page_title="Ad Transparency Agent", layout="wide")\
\
st.title("\uc0\u55357 \u56522  Ad Transparency & Scraper Agent")\
st.write("Search Google Ad Transparency and Meta Ads Library for active ads.")\
\
# Input form\
query = st.text_input("\uc0\u55357 \u56589  Enter keyword to search ads:", "")\
source = st.selectbox("Choose source:", ["Google Ads Transparency", "Meta Ads Library"])\
\
if st.button("Search"):\
    if not query.strip():\
        st.warning("\uc0\u9888 \u65039  Please enter a keyword first.")\
    else:\
        st.info(f"Fetching ads for **\{query\}** from **\{source\}** ...")\
\
        # Fake demo results (so app works even without API keys)\
        if source == "Google Ads Transparency":\
            demo_data = [\
                \{"Advertiser": "Google Demo Corp", "Ad Title": f"\{query\} Offer", "Impressions": "120K", "Status": "Active"\},\
                \{"Advertiser": "Search Ads Ltd", "Ad Title": f"Buy \{query\} Today", "Impressions": "95K", "Status": "Active"\},\
            ]\
        else:  # Meta Ads Library\
            demo_data = [\
                \{"Advertiser": "Meta Demo Brand", "Ad Title": f"\{query\} Special Deal", "Impressions": "210K", "Status": "Active"\},\
                \{"Advertiser": "FB Ads Partner", "Ad Title": f"New \{query\} Ads", "Impressions": "180K", "Status": "Active"\},\
            ]\
\
        df = pd.DataFrame(demo_data)\
\
        # Show results\
        st.subheader("\uc0\u55357 \u56520  Results")\
        st.dataframe(df, use_container_width=True)\
\
        # Option to download CSV\
        csv = df.to_csv(index=False).encode("utf-8")\
        st.download_button(\
            label="\uc0\u55357 \u56549  Download results as CSV",\
            data=csv,\
            file_name=f"\{query\}_ads.csv",\
            mime="text/csv",\
        )\
\
st.caption("\uc0\u9889  Demo Mode: This app shows sample ads. Real API integration comes later.")\
}