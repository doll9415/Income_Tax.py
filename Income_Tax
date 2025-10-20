import streamlit as st

st.title("소득 수준 분류기")

income = st.number_input("소득을 입력하세요 (만원)", min_value=0, step=100)

if income >= 7000:
    level = "고소득자"
    tax = income * 0.5
elif income >= 4000:
    level = "중간소득자"
    tax = income * 0.25
else:
    level = "저소득자"
    tax = income * 0.1

st.write(f"**소득:** {income} 만원")
st.write(f"**분류:** {level}")
st.write(f"**예상 세금:** {tax:.1f} 만원")
