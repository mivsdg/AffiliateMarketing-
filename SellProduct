import streamlit as st

st.set_page_config(page_title="Amazon Deals Hub", layout="wide")

st.title("Amazon Deals Hub")
st.markdown("### Handpicked Amazon Deals with Affiliate Links")

# Featured Products
products = [
    {
        "name": "Awesome Gadget",
        "desc": "Top-rated tech gadget that improves productivity.",
        "img": "https://via.placeholder.com/300x200",
        "url": "https://www.amazon.com/dp/B000000000?tag=youraffiliatetag"
    },
    {
        "name": "Smart Kitchen Tool",
        "desc": "Must-have kitchen tool for every home chef.",
        "img": "https://via.placeholder.com/300x200",
        "url": "https://www.amazon.com/dp/B000000001?tag=youraffiliatetag"
    },
    {
        "name": "Fitness Tracker",
        "desc": "Track your health goals effectively with this smart device.",
        "img": "https://via.placeholder.com/300x200",
        "url": "https://www.amazon.com/dp/B000000002?tag=youraffiliatetag"
    }
]

cols = st.columns(3)
for col, product in zip(cols, products):
    with col:
        st.image(product["img"], use_column_width=True)
        st.subheader(product["name"])
        st.caption(product["desc"])
        st.markdown(f"[Buy on Amazon]({product['url']})", unsafe_allow_html=True)

st.markdown("---")
st.caption("© 2025 Amazon Deals Hub. This site contains affiliate links.")
