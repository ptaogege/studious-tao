# Telephone 类：（电话本信息）
package com.tao.bean;

public class Telephone {
    private String name;
    private String sex;
    private int age;
    private int tel;
    private int qq;
    private String address;

    public Telephone(String name, String sex, int age, int tel, int qq, String address) {
        this.name = name;
        this.sex = sex;
        this.age = age;
        this.tel = tel;
        this.qq = qq;
        this.address = address;
    }

    public Telephone() {
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getSex() {
        return sex;
    }

    public void setSex(String sex) {
        this.sex = sex;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public int getTel() {
        return tel;
    }

    public void setTel(int tel) {
        this.tel = tel;
    }

    public int getQq() {
        return qq;
    }

    public void setQq(int qq) {
        this.qq = qq;
    }

    public String getAddress() {
        return address;
    }

    public void setAddress(String address) {
        this.address = address;
    }

    @Override
    public String toString() {
        return "Telephone{" +
                "name='" + name + '\'' +
                ", sex='" + sex + '\'' +
                ", age=" + age +
                ", tel=" + tel +
                ", qq=" + qq +
                ", address='" + address + '\'' +
                '}';
    }
}
