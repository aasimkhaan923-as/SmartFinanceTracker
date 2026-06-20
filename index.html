import React, { useState } from 'react';
import { 
  StyleSheet, 
  Text, 
  View, 
  ScrollView, 
  TextInput, 
  TouchableOpacity, 
  StatusBar, 
  SafeAreaView, 
  Platform 
} from 'react-native';

export default function App() {
  // تھیم کی اسٹیٹ (Default: VIP Dark Mode)
  const [isDarkMode, setIsDarkMode] = useState(true);

  // ڈمی ڈیٹا (تاکہ ابھی اسکرین پر فنانس کا لائیو حساب کتاب نظر آئے)
  const [totals, setTotals] = useState({
    income: "55,000",
    expense: "12,500",
    cash: "30,000",
    bank: "12,500",
    borrowed: "5,000",
    lent: "2,000"
  });

  return (
    <SafeAreaView style={[styles.container, isDarkMode ? styles.darkBg : styles.lightBg]}>
      <StatusBar barStyle={isDarkMode ? "light-content" : "dark-content"} />
      
      {/* 1. ہیڈر سیکشن */}
      <View style={[styles.header, isDarkMode ? styles.darkCard : styles.lightCard]}>
        <Text style={[styles.headerTitle, isDarkMode ? styles.darkText : styles.lightText]}>
          📊 حساب کتاب - ورژن 7.0 پرو
        </Text>
        <TouchableOpacity 
          style={[styles.themeBtn, isDarkMode ? styles.darkBadge : styles.lightBadge]}
          onPress={() => setIsDarkMode(!isDarkMode)}
        >
          <Text style={{ fontSize: 18 }}>{isDarkMode ? '☀️' : '🌙'}</Text>
        </TouchableOpacity>
      </View>

      <ScrollView showsVerticalScrollIndicator={false} contentContainerStyle={{ paddingBottom: 30 }}>
                {/* 2. ڈیش بورڈ کارڈز گرڈ */}
        <View style={styles.gridContainer}>
          {/* پہلی رو: آمدنی اور خرچہ */}
          <View style={styles.gridRow}>
            <View style={[styles.card, styles.cardIncome, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>📈 کل آمدنی</Text>
              <Text style={[styles.amount, { color: '#10b981' }]}>{totals.income}</Text>
            </View>
            <View style={[styles.card, styles.cardExpense, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>📉 کل خرچہ</Text>
              <Text style={[styles.amount, { color: '#ef4444' }]}>{totals.expense}</Text>
            </View>
          </View>

          {/* دوسری رو: کیش اور بینک */}
          <View style={styles.gridRow}>
            <View style={[styles.card, styles.cardCash, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>💵 نقد کیش</Text>
              <Text style={[styles.amount, { color: '#0ea5e9' }]}>{totals.cash}</Text>
            </View>
            <View style={[styles.card, styles.cardBank, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>🏦 بینک بیلنس</Text>
              <Text style={[styles.amount, { color: '#6366f1' }]}>{totals.bank}</Text>
            </View>
          </View>

          {/* تیسری رو: ادھار لیا/دیا */}
          <View style={styles.gridRow}>
            <View style={[styles.card, styles.cardBorrowed, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>🤝 ادھار لیا</Text>
              <Text style={[styles.amount, { color: '#8b5cf6' }]}>{totals.borrowed}</Text>
            </View>
            <View style={[styles.card, styles.cardLent, isDarkMode ? styles.darkCard : styles.lightCard]}>
              <Text style={[styles.cardTitle, isDarkMode ? styles.darkText : styles.lightText]}>💸 ادھار دیا</Text>
              <Text style={[styles.amount, { color: '#ec4899' }]}>{totals.lent}</Text>
            </View>
          </View>
        </View>
                    {/* 3. نیا اندراج فارم (Data Entry Form) */}
        <View style={[styles.mainBox, isDarkMode ? styles.darkCard : styles.lightCard]}>
          <Text style={[styles.boxTitle, isDarkMode ? styles.darkText : styles.lightText]}>📝 نیا لین دین درج کریں</Text>
          
          <View style={styles.formGroup}>
            <Text style={[styles.label, isDarkMode ? styles.darkText : styles.lightText]}>رقم لکھیں (Rs.):</Text>
            <TextInput 
              style={[styles.input, isDarkMode ? styles.darkInput : styles.lightInput]} 
              placeholder="0.00" 
              placeholderTextColor="#94a3b8"
              keyboardType="numeric"
            />
          </View>

          <View style={styles.formGroup}>
            <Text style={[styles.label, isDarkMode ? styles.darkText : styles.lightText]}>تفصیل (جیسے: پٹرول، راشن):</Text>
            <TextInput 
              style={[styles.input, isDarkMode ? styles.darkInput : styles.lightInput]} 
              placeholder="تفصیل لکھیں..." 
              placeholderTextColor="#94a3b8"
            />
          </View>

          {/* ایکشن بٹنز */}
          <View style={styles.btnGrid}>
            <TouchableOpacity style={[styles.actionBtn, { backgroundColor: '#10b981' }]}>
              <Text style={styles.btnText}>➕ آمدنی</Text>
            </TouchableOpacity>
            <TouchableOpacity style={[styles.actionBtn, { backgroundColor: '#ef4444' }]}>
              <Text style={styles.btnText}>➖ خرچہ</Text>
            </TouchableOpacity>
          </View>
        </View>

      </ScrollView>
    </SafeAreaView>
  );
          }
            const styles = StyleSheet.create({
  container: {
    flex: 1,
    paddingTop: Platform.OS === 'android' ? StatusBar.currentHeight + 10 : 10,
  },
  darkBg: { backgroundColor: '#0f172a' },
  lightBg: { backgroundColor: '#f4f6f9' },
  header: {
    flexDirection: 'row-reverse',
    justifyContent: 'space-between',
    alignItems: 'center',
    padding: 16,
    marginHorizontal: 15,
    borderRadius: 16,
    elevation: 4,
    shadowColor: '#000',
    shadowOffset: { width: 0, height: 2 },
    shadowOpacity: 0.1,
    shadowRadius: 4,
    marginBottom: 15,
  },
  darkCard: { backgroundColor: '#1e293b', borderColor: '#334155', borderWidth: 1 },
  lightCard: { backgroundColor: '#ffffff', borderColor: '#e0e4ec', borderWidth: 1 },
  headerTitle: { fontSize: 18, fontWeight: 'bold' },
  darkText: { color: '#f8fafc' },
  lightText: { color: '#2b2d42' },
  themeBtn: { width: 40, height: 40, borderRadius: 20, alignItems: 'center', justifyContents: 'center', justifyContent: 'center' },
  darkBadge: { backgroundColor: '#334155' },
  lightBadge: { backgroundColor: '#f1f5f9' },
  
  // گرڈ ڈیزائن
  gridContainer: { paddingHorizontal: 15, gap: 12, marginBottom: 15 },
  gridRow: { flexDirection: 'row-reverse', gap: 12 },
  card: { flex: 1, padding: 14, borderRadius: 16, alignItems: 'center', elevation: 3, borderTopWidth: 5 },
  cardTitle: { fontSize: 13, fontWeight: '600', marginBottom: 6, opacity: 0.9 },
  amount: { fontSize: 18, fontWeight: 'bold' },
  
  // کارڈز کی رنگ برنگی ٹاپ پٹیاں
  cardIncome: { borderTopColor: '#10b981' },
  cardExpense: { borderTopColor: '#ef4444' },
  cardCash: { borderTopColor: '#0ea5e9' },
  cardBank: { borderTopColor: '#6366f1' },
  cardBorrowed: { borderTopColor: '#8b5cf6' },
  cardLent: { borderTopColor: '#ec4899' },
  
  // فارم ڈیزائن
  mainBox: { marginHorizontal: 15, padding: 16, borderRadius: 16, elevation: 3 },
  boxTitle: { fontSize: 16, fontWeight: 'bold', marginBottom: 15, textAlign: 'right' },
  formGroup: { marginBottom: 12 },
  label: { fontSize: 13, fontWeight: '600', marginBottom: 6, textAlign: 'right' },
  input: { padding: 12, borderRadius: 10, fontSize: 14, textAlign: 'right', borderWidth: 1 },
  darkInput: { backgroundColor: '#0f172a', color: '#f8fafc', borderColor: '#334155' },
  lightInput: { backgroundColor: '#f8fafc', color: '#2b2d42', borderColor: '#e0e4ec' },
  
  // بٹنز
  btnGrid: { flexDirection: 'row-reverse', gap: 12, marginTop: 10 },
  actionBtn: { flex: 1, padding: 14, borderRadius: 12, alignItems: 'center', justifyContent: 'center', elevation: 2 },
  btnText: { color: '#ffffff', fontSize: 15, fontWeight: 'bold' }
});
