# Practice-Python-28---pdf-watermark

from pikepdf import Pdf, Page, Rectangle

old_pdf1 = Pdf.open("Policy_Certificate_49982828_25122023_policyPDF.pdf")
old_pdf2 = Pdf.open("THIRD SEM FEES RECEIPT 6000.pdf")
des_page = Page(old_pdf1.pages[0])
sur_page = Page(old_pdf2.pages[0])

des_page.add_overlay(sur_page, Rectangle(0, 0, 500, 500))
old_pdf1.save("aaabbbccc.pdf")
